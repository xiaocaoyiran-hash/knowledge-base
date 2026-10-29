# 研选家运营知识库

公开访问地址：https://xiaocaoyiran-hash.github.io/knowledge-base/

网站包含两个知识模块和一组常用运营入口：

- PPT 技能图鉴、使用说明与快速选型。
- 站长实战方法库，保留原版检索、筛选与来源信息。
- 10 组日常运营查询，共 13 个链接，支持分类和搜索。

## 发布与更新

本仓库根目录即静态网站，无需安装依赖或构建。GitHub Pages 使用 `main` 分支的根目录发布。将修改提交到 `main` 后，会自动更新网站。

- 页面结构：`index.html`；`resources.html` 保留为兼容入口。
- 页面样式：`deck.css`。
- 翻页、筛选与查询链接：`deck.js`。
- 动态背景：`atmosphere.js`。
- 站长方法库：`resources/station-methods.html`。
- 网站视觉素材：`assets/`。

本地可使用任意静态 HTTP 服务器预览。保持资源相对路径，以兼容 GitHub Pages 的 `/knowledge-base/` 子路径。

日常运营查询链接以提供的地址为准，BI 链接保留完整参数。

## 资料与设计来源

- [PPT Skills 图鉴](https://xiaocaoyiran-hash.github.io/yanxuanjia-ppt-skills-web/)
- [图鉴使用说明书](https://xiaocaoyiran-hash.github.io/ppt-skills-manual/#ops)
- 站长方法库为提供的 2026-10-26 HTML 版本，原文内容保持不变。
- 网站视觉采用提供的研选家品牌资料，未提供品牌原始文档的公开下载。
- 动态背景中的 Grainient shader 来自 React Bits，经 Framesbase MCP 获取并适配原生 WebGL2：[组件来源](https://framesbase.app/reactbits/backgrounds/grainient)。
- 标题呈现与演示导航参考 Framesbase 的 Masked Heading 和 Pro AI Deck，已适配为静态页面交互。

此仓库不包含 Sites 身份信息、部署凭据、浏览器本地数据或内部制作文件。
