# test-other-repo

零框架、零依赖的纯 HTML 静态项目。页面样式直接写在 `index.html` 中，无需编译即可用浏览器打开。

## 环境

Node.js 18 或更新版本，以及 npm。

## 安装与构建

```sh
npm install
npm run build
```

构建使用 Node.js 内置文件系统模块，将 `index.html` 复制到 `dist/index.html`。不下载第三方构建工具，不使用任何前端框架。

## 开发与部署

编辑根目录的 `index.html`，在浏览器中打开并刷新即可预览。修改后重新运行 `npm run build`，将 `dist/` 目录部署到任意静态网站托管服务。

`dist/` 是生成产物，不纳入 Git 版本管理。
