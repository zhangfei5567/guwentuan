# 顾问团

顾问团项目仓库。

## 说明

本仓库为独立项目，与本地其他项目无关。

## 每日复盘系统

本项目内置 Cursor 技能 **daily-review**，支持：

1. **记录** — 结构化记录每日复盘
2. **提炼** — 从复盘内容提取核心要点
3. **讨论** — 基于要点进行深度分析与建议

### 快速开始

在 Cursor 对话中输入：

```
/daily-review
```

或直接说：

- 「帮我复盘今天」
- 「提炼一下今天的要点」
- 「讨论一下今天的复盘」

### 文件位置

| 内容 | 路径 |
|------|------|
| 技能定义 | `.cursor/skills/daily-review/SKILL.md` |
| 复盘模板 | `.cursor/skills/daily-review/references/template.md` |
| 复盘记录 | `reviews/YYYY-MM-DD.md` |
| 要点摘要 | `reviews/insights/YYYY-MM-DD-summary.md` |
| 复盘索引 | `reviews/INDEX.md` |
