# 小游戏合集

一个使用原生 HTML、CSS 和 JavaScript 编写的静态小游戏项目。目前包含入口页、贪吃蛇和连连看两个游戏页面。

## 游戏内容

- `index.html`：游戏合集入口页
- `snake.html`：贪吃蛇游戏，支持分数统计和最佳分数记录
- `lianliankan.html`：连连看游戏，支持计时、提示、重排和暂停

## 运行方式

项目不需要安装依赖，直接用浏览器打开 `index.html` 即可开始游玩。

也可以使用本地静态服务器运行，例如：

```powershell
python -m http.server 8000
```

然后在浏览器访问：

```text
http://localhost:8000
```

## 项目结构

```text
.
+-- index.html
+-- lianliankan.html
+-- snake.html
+-- README.md
```

## 技术栈

- HTML
- CSS
- JavaScript

## 说明

这是一个前端练习项目，所有游戏逻辑和界面样式都写在对应的 HTML 文件中，适合直接部署到 GitHub Pages 等静态站点服务。
