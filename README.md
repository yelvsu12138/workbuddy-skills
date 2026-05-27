# WorkBuddy 技能集合

这是一个 WorkBuddy AI 助手的技能集合仓库。

## 包含的技能

### 1. 前端简历修改工具 (frontend-resume-editor)
- **功能**: 修改前端简历，支持 Markdown、HTML、JSON 格式
- **触发词**: 修改简历、编辑简历、更新简历、前端简历、resume
- **位置**: `frontend-resume-editor/`

### 2. 简历助手 (resume-assistant)
- **功能**: 面向中国求职者的可追溯 JD 定制简历助手
- **特点**: 
  - 支持从 master 简历派生多版本
  - 三维度防幻觉（不编造数字/合法改写/防 AI 味）
  - 输出中英双版简历 + 战略附录 + ATS 友好 PDF
- **触发词**: 写简历、生成简历、简历润色、简历改写、按 JD 改简历、简历打分、简历多版本、中英双版简历
- **位置**: `resume-assistant/`
- **作者**: TPD
- **版本**: 1.0.0

## 使用方法

1. 将技能目录复制到你的 `~/.workbuddy/skills/` 目录下
2. 重启 WorkBuddy
3. 使用自然语言与 AI 交流来调用技能

## 技能文件结构

```
workbuddy-skills/
├── frontend-resume-editor/
│   ├── SKILL.md           # 技能说明文件
│   └── _skillhub_meta.json # 技能元数据
├── resume-assistant/
│   ├── SKILL.md           # 技能说明文件
│   ├── _skillhub_meta.json # 技能元数据
│   ├── assets/            # 模板和主题文件
│   ├── modes/             # 不同工作模式
│   ├── references/        # 参考文档和规则
│   └── scripts/           # 辅助脚本
└── README.md
```

## 贡献

欢迎贡献新的技能！请按照以下格式创建技能目录：
- `SKILL.md`: 技能说明文件
- `_skillhub_meta.json`: 技能元数据

## 许可证

MIT License