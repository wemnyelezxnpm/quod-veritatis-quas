# String.raw <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `String.raw` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-@wemnyelezxnpm/quod-veritatis-quas).

## Getting started

```sh
npm install --save @wemnyelezxnpm/quod-veritatis-quas
```

## Usage/Examples

```js
// Create Windows path without escaping the backslashes:
const filePath = String.raw`C:\Development\profile\new\aboutme.html`;

console.log(`${filePath}`); // "C:\Development\profile\new\aboutme.html"
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/wemnyelezxnpm/quod-veritatis-quas
[npm-version-svg]: https://versionbadg.es/wemnyelezxnpm/quod-veritatis-quas.svg
[deps-svg]: https://david-dm.org/wemnyelezxnpm/quod-veritatis-quas.svg
[deps-url]: https://david-dm.org/wemnyelezxnpm/quod-veritatis-quas
[dev-deps-svg]: https://david-dm.org/wemnyelezxnpm/quod-veritatis-quas/dev-status.svg
[dev-deps-url]: https://david-dm.org/wemnyelezxnpm/quod-veritatis-quas#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/wemnyelezxnpm/quod-veritatis-quas.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/wemnyelezxnpm/quod-veritatis-quas.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/wemnyelezxnpm/quod-veritatis-quas.svg
[downloads-url]: https://npm-stat.com/charts.html?package=wemnyelezxnpm/quod-veritatis-quas
[codecov-image]: https://codecov.io/gh/wemnyelezxnpm/quod-veritatis-quas/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/wemnyelezxnpm/quod-veritatis-quas/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/wemnyelezxnpm/quod-veritatis-quas
[actions-url]: https://github.com/wemnyelezxnpm/quod-veritatis-quas/actions
