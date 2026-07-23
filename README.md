# Poster Layer

## Lovart Poster Layering v3.1

将海报或营销参考图拆分为完整、可独立编辑的全画布图层。适用于主体抠图、遮挡区域修复、基于原图证据的图形/UI 拆分、绿幕图层准备和重新合成。

### 核心原则

- 每个图层保留原始画布尺寸与坐标。
- 仅补全结构明确的遮挡区域；锁定可见角色、文字、Logo 和背景锚点。
- 标题、日期、CTA、Logo、图标和前景特效按独立编辑需求拆分。
- 每层仅生成一个候选，不自动重试。
- 文字突变、位置漂移、角色重绘、错误解剖、未见图形效果或背景重绘会被拒绝，不会作为最终图层交付。

### 使用

在支持 Codex Skills 的环境中安装 `lovart-poster-layering-v3-1/`，然后引用该 Skill 并上传海报参考图。

该版本用于验收测试，保持不可变；后续改动应创建新的版本目录，而非覆盖 v3.1。

### 相关链接

- [飞书文档](https://my.feishu.cn/wiki/CaYZw2QiKizHw9kaCgdczlvWnHe?from=from_copylink)

### 文件结构

```text
lovart-poster-layering-v3-1/
├── SKILL.md
├── assets/layer-manifest.json
├── references/
│   ├── layer-rules.md
│   └── prompt-templates.md
└── agents/openai.yaml
```
