# spraygun-react-ts

[![CircleCI](https://circleci.com/gh/carbonfive/spraygun-react/tree/master.svg?style=svg)](https://circleci.com/gh/carbonfive/spraygun-react/tree/master)

This is a Carbon Five-flavored convenience skeleton project for React with TypeScript. It is based on create-react-app-ts (not ejected) with the following additions:

- Styling via .scss with BEM conventions
- Stylelint
- TSLint/Prettier
- Husky with lint-staged
- CI testing via Circle CI
- Deployable to Heroku out of the box
- Or deploy via docker using the included Dockerfile

To get started, make sure you have Node 8.10+ and Yarn installed, and then generate your project like this:

```
$ npx spraygun -t react-ts <project-directory>
```

If you'd like to use spraygun-react-ts with a Rails API backend, follow this guide:

> [Using spraygun-react with a Rails backend](./docs/how-to-use-with-rails-backend.md)

_Below this line is the README that will accompany your generated project._

---

<!-- END SPRAYGUN BANNER -->

# app-prototype

This is a React 16 app.

## Prerequisites

- Node 8.12.0
- Yarn 1.9.4

## Quick start

Install dependencies:

```
yarn install
```

Start the server:

```
yarn start
```

This will launch the app at:

<http://localhost:3000/>

## Task reference

- **`yarn start`** starts the development server listing on port 3000. Changes to .ts or .scss files automatically refresh in the browser.
- **`yarn test`** runs tests in "watch" mode, automatically focusing on tests or code that were modified since the last commit. Press the `a` key after the test runner has started to watch all tests in the project.
- **`yarn test:coverage`** runs all tests, prints coverage stats, and then exits.
- **`yarn lint`** runs all ESLint checks and then exits.
- **`yarn build`** generates an optimized bundle of the app into the `build` directory, suitable for deployment.

---

_Generated by [spraygun-react](https://github.com/carbonfive/spraygun-react)_
