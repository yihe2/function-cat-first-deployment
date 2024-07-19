# 模板介绍

 - 原始项目地址： [AstroPaper](https://github.com/satnaing/astro-paper) 。

 - 原始项目Star： [![GitHub stars](https://img.shields.io/github/stars/satnaing/astro-paper?style=social)](https://github.com/satnaing/astro-paper/stargazers)

以下是原始项目的 README 内容：

---

<!-- 这里开始是原来的 fork 源项目的 README.md 内容 -->
# AstroPaper 📄



![AstroPaper](public/astropaper-og.jpg)
[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/community/file/1356898632249991861)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![GitHub](https://img.shields.io/github/license/satnaing/astro-paper?color=%232F3741&style=for-the-badge)
[![常规提交](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white&style=for-the-badge)](https://conventionalcommits.org)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=for-the-badge)](http://commitizen.github.io/cz-cli/)

AstroPaper 是一款极简、响应迅速、可访问且 SEO 友好的 Astro 博客主题。此主题是根据 [我的个人博客](https://satnaing.dev/blog) 设计和制作的。

此主题遵循最佳实践并提供开箱即用的可访问性。默认情况下支持浅色和深色模式。此外，还可以配置其他配色方案。

此主题是自文档化的 \_ 这意味着此主题中的文章/帖子也可以视为文档。阅读[博客文章](https://astro-paper.pages.dev/posts/) 或查看[README 文档部分](#-documentation) 了解更多信息。

## 🔥 功能

- [x] 类型安全 markdown
- [x] 超快性能
- [x] 可访问（键盘/VoiceOver）
- [x] 响应式（移动 ~ 桌面）
- [x] SEO 友好
- [x] 明暗模式
- [x] 模糊搜索
- [x] 草稿帖子和分页
- [x] 站点地图和 RSS 源
- [x] 遵循最佳实践
- [x] 高度可定制
- [x] 动态 OG 图像生成用于博客文章 [#15](https://github.com/satnaing/astro-paper/pull/15) ([博客文章](https://astro-paper.pages.dev/posts/dynamic-og-image-generation-in-astropaper-blog-posts/))

_注意：我已经使用 Mac 上的 **VoiceOver** 和 Android 上的 **TalkBack** 测试了 AstroPaper 的屏幕阅读器可访问性。我无法测试所有其他的屏幕阅读器。但是，AstroPaper 中的可访问性增强功能在其他版本上也应该可以正常工作。_

## ✅ Lighthouse Score

<p align="center">
<a href="https://pagespeed.web.dev/report?url=https%3A%2F%2Fastro-paper.pages.dev%2F&form_factor=desktop">
<img width="710" alt="AstroPaper Lighthouse Score" src="AstroPaper-lighthouse-score.svg">
<a>
</p>

## 🚀 项目结构

在 AstroPaper 内部，您将看到以下文件夹和文件：

```bash
/
═── public/
│ ═── assets/
│ │ └── logo.svg
│ │ └── logo.png
│ └── favicon.svg
│ └── astropaper-og.jpg
│ └── robots.txt
│ └── toggle-theme.js
│ └── toggle-theme.js
│ └── src/
│ └── assets/
│ │ └── socialIcons.ts
│ └── components/
│ └── content/
│ │ | blog/
│ │ | └── some-blog-posts.md
│ │ └── config.ts
│ └── layouts/
│ └── pages/
│ └── style/
│ └── utils/
│ └── config.ts
│ └── types.ts
└── package.json
```

Astro 在 `src/pages/` 目录中查找 `.astro` 或 `.md` 文件。每个页面都根据其文件名显示为路由。

任何静态资产（如图像）都可以放在 `public/` 目录中。

所有博客文章都存储在`src/content/blog`目录中。

## 📖 文档

文档可以以两种格式阅读\_ _markdown_ 和 _blog post_。

- 配置 - [markdown](src/content/blog/how-to-configure-astropaper-theme.md) | [blog post](https://astro-paper.pages.dev/posts/how-to-configure-astropaper-theme/)
- 添加帖子 - [markdown](src/content/blog/adding-new-post.md) | [blog post](https://astro-paper.pages.dev/posts/adding-new-posts-in-astropaper-theme/)
- 自定义配色方案 - [markdown](src/content/blog/customizing-astropaper-theme-color-schemes.md) | [博客文章](https://astro-paper.pages.dev/posts/customizing-astropaper-theme-color-schemes/)
- 预定义配色方案 - [markdown](src/content/blog/predefined-color-schemes.md) | [博客文章](https://astro-paper.pages.dev/posts/predefined-color-schemes/)

> 对于 AstroPaper v1，请查看 [此分支](https://github.com/satnaing/astro-paper/tree/astro-paper-v1) 和此 [实时 URL](https://astro-paper-v1.astro-paper.pages.dev/)

## 💻 技术堆栈

**主框架** - [Astro](https://astro.build/)
**类型检查** - [TypeScript](https://www.typescriptlang.org/)
**组件框架** - [ReactJS](https://reactjs.org/)
**样式** - [TailwindCSS](https://tailwindcss.com/)
**UI/UX** - [Figma 设计文件](https://www.figma.com/community/file/1356898632249991861)
**模糊搜索** - [FuseJS](https://fusejs.io/)
**图标** - [Boxicons](https://boxicons.com/) | [Tablers](https://tabler-icons.io/)
**代码格式化** - [Prettier](https://prettier.io/)
**部署** - [Cloudflare Pages](https://pages.cloudflare.com/)
**关于页面中的插图** - [https://freesvgillustration.com](https://freesvgillustration.com/)
**Linting** - [ESLint](https://eslint.org)

## 👨🏻‍💻 本地运行

您可以通过在所需目录中运行以下命令开始在本地使用此项目：

```bash
# npm 6.x
npm create astro@latest --template satnaing/astro-paper

# npm 7+，需要额外的双破折号：
npm create astro@latest -- --template satnaing/astro-paper

# yarn
yarn create astro --template satnaing/astro-paper

# pnpm
pnpm dlx create-astro --template satnaing/astro-paper
```

然后通过运行以下命令启动项目：

```bash
# prepare commit hook & install dependency
npm run prepare && npm run install

# start running the project
npm run dev
```

作为替代方法，如果您已安装 Docker，则可以使用 Docker 在本地运行此项目。方法如下：

```bash
# 构建 Docker 映像
docker build -t astropaper 。

# 运行 Docker 容器
docker run -p 4321:80 astropaper
```

## Google 站点验证（可选）

您可以使用环境变量在 AstroPaper 中轻松添加 [Google 站点验证 HTML 标签](https://support.google.com/webmasters/answer/9008080#meta_tag_verification&zippy=%2Chtml-tag)。此步骤是可选的。如果您不添加以下环境变量，google-site-verification 标签将不会出现在 html `<head>` 部分中。

```bash
# 在您的环境变量文件 (.env) 中
PUBLIC_GOOGLE_SITE_VERIFICATION=your-google-site-verification-value
```

## 🧞 命令

所有命令均从项目根目录的终端运行：

> **_注意！_** 对于 `Docker` 命令，我们必须在您的机器上 [安装](https://docs.docker.com/engine/install/)。

| 命令 | 操作 |
| :----------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------- |
| `npm install` | 安装依赖项 |
| `npm run dev` | 在 `localhost:4321` 启动本地开发服务器 |
| `npm run build` | 将您的生产站点构建到 `./dist/` |
| `npm run preview` | 在部署之前在本地预览您的构建 |
| `npm run format:check` |使用 Prettier 检查代码格式 |
| `npm run format` | 使用 Prettier 格式化代码 |
| `npm run sync` | 为所有 Astro 模块生成 TypeScript 类型。[了解更多](https://docs.astro.build/en/reference/cli-reference/#astro-sync)。|
| `npm run cz` | 使用 commitizen 提交代码更改 |
| `npm run lint` | 使用 ESLint 进行 Lint |
| `docker compose up -d` | 在 docker 上运行 AstroPaper，您可以使用在 `dev` 命令中告知的相同主机名和端口进行访问。|
| `docker compose run app npm install` | 您可以在 docker 容器中运行上述任何命令。|
| `docker build -t astropaper .` | 为 AstroPaper 构建 Docker 映像。|
| `docker run -p 4321:80 astropaper` | 在 Docker 上运行 AstroPaper。该网站将可通过 `http://localhost:4321` 访问。|

> **_警告！_** 如果 Windows PowerShell 用户想要在开发期间 [运行诊断程序](https://docs.astro.build/en/reference/cli-reference/#astro-check)（`astro check --watch & astro dev`），则可能需要安装 [concurrently 包](https://www.npmjs.com/package/concurrently)。有关更多信息，请参阅 [此问题](https://github.com/satnaing/astro-paper/issues/113)。

## ✨ 反馈和建议

如果您有任何建议/反馈，您可以通过 [我的电子邮件](mailto:contact@satnaing.dev) 与我联系。或者，如果您发现错误或想要请求新功能，请随时打开问题。

## 📜 许可证

根据 MIT 许可证授权，版权所有 © 2023

---

由 [Sat Naing](https://satnaing.dev) 👨🏻‍💻 和 [贡献者](https://github.com/satnaing/astro-paper/graphs/contributors) 使用 🤍 制作。

