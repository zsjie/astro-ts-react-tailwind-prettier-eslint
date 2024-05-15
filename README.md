# Astro Starter Kit: Basic Template with Typescript, React, Tailwind, Prettier and Eslint

```sh
npm create astro@latest -- --template zsjie/astro-ts-react-tailwind-prettier-eslint
```

## 🔥 Features

This template is a customized version of [Basic Astro Starter kit](https://github.com/withastro/astro/tree/main/examples/basics), with following features:

-   ✅ [React 18](https://react.dev)
-   ✅ [Tailwindcss](https://tailwindcss.com/)
-   ✅ Astro component and react component lint with [Eslint](https://eslint.org), auto-fixes on save
-   ✅ File formatting with [Prettier](https://prettier.io), auto format on save and on paste
-   ✅ Import Alias
-   ✅ use [Yarn](https://yarnpkg.com) as package manager

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                    | Action                                           |
| :------------------------- | :----------------------------------------------- |
| `yarn`                     | Installs dependencies                            |
| `yarn run dev`             | Starts local dev server at `localhost:4321`      |
| `yarn run build`           | Build your production site to `./dist/`          |
| `yarn run preview`         | Preview your build locally, before deploying     |
| `yarn run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `yarn run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
