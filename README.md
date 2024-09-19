# fuck-cors-to-cf

## 摧毁cors完整部署方式

# 声明

## 当你无聊到对别人公共的服务器进行恶意攻击，那你不如有时间在拼多多拼个妈

## 部署

### 环境准备

1. **环境变量配置**

  清除环境变量：
  
  ```bash
  set CLOUDFLARE_API_TOKEN=
  ```

2. **依赖安装**

  - 确保 Node.js 和 npm 已安装
在命令提示符中，输入以下命令来检查是否已安装 Node.js 和 npm：

  ```bash
  node -v
  npm -v
  ```

  - 全局安装 Wrangler：
  
  ```bash
  npm install -g wrangler
  ```

3.**登录cf账号**

在控制台登录：

  ```bash
  wrangler login
  ```

4. **部署到 Cloudflare**

使用以下命令将 Workers 部署到 Cloudflare：

  ```bash
  npx wrangler publish
  ```

5.**完成部署**
接下来就可以愉快地到处 fetch 啦！

