# OpenClaw Team Dashboard

2D 像素风格可视化仪表盘，用于展示 OpenClaw 多 Agent 团队状态。

## 功能

- 🎮 **可拖拽像素形象** — 4 个 Agent 都有独立像素 avatar
- 📋 **点击查看详情** — 专长、模型、状态一目了然
- 🔄 **实时状态栏** — 显示 Agent 数量和最后更新时间
- 🕹️ **复古 CRT 滤镜** — 像素扫描线效果

## 预览

直接在浏览器打开 `index.html` 即可使用：

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

## Agent 角色

| Agent | 角色 | 专长 |
|-------|------|------|
| 🖥️ Pilot | 仪表盘前台 | 接待、引导、任务分流 |
| ⚙️ Sysop | 运维工程师 | 配置管理、健康检查 |
| 🎨 Muse | 创意设计师 | Persona 设计 |
| 📜 Scribe | 历史记录员 | 经验沉淀、记忆管理 |

## 技术栈

- 纯前端单文件（无依赖）
- CSS Pixel Art 渲染
- 原生拖拽 API
- CRT 扫描线滤镜
