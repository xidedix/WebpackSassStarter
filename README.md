# Intention

This repository has been created in order to have a minimal FE setup for any application architecture based on web components.

It uses Sass (with .scss/.sass). The style is loaded at the component level.

Dependencies can be handled by **Yarn**.

See the example in the `src` folder for a basic usage of this starter kit.

**HMR doesn't work properly**
At the moment `watchContentBase` is set to `true` as a fallback

http://stackoverflow.com/questions/42624778/webpack-hot-module-replacement-does-not-inject-the-updated-code?noredirect=1#comment73202885_42624778

Needs to investigate into this
https://webpack.js.org/guides/hmr-react/

TODO
- create a new repository for React FEsetup that uses HMR

## Usage
- `yarn` to install dependencies

- `npm run start:dev` for developing (it runs build:dev and webpack-dev-server)
- `npm run start:server` to startup webserver (for production testings)

- `npm run build:dev` to run a dev build
- `npm run build:prod`to run production build

- `npm run lint:js` lints javascript
- `npm run lint:css`  lints css
- `npm run lint:html` lints html
- `npm run lint` run all the linters

- `npm test` run the test suites
