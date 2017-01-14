# webapp-cli

A simple CLI for create webapp projects.

### Installation

Prerequisites: [Node.js](https://nodejs.org/en/) (>=4.x, 6.x preferred) and [Git](https://git-scm.com/).

``` bash
$ npm install -g webapp-cli
```

### Usage

``` bash
$ webapp init <template-name> <project-name>
```

Example:

``` bash
$ webapp init webpack my-project
```

The above command pulls the template from [webapp-templates/webpack](https://github.com/zhouzhihu/webpack), prompts for some information, and generates the project at `./my-project/`.

### Official Templates

Current available templates include:

- [webpack](https://github.com/zhouzhihu/webpack) - SPA Page, A full-featured Webpack + vue-loader setup with hot reload, linting, testing & css extraction.

- [webpack-multi](https://github.com/vuejs-templates/webpack-multi) - Multi Page, A full-featured Webpack + vue-loader setup with hot reload, linting, testing & css extraction.


### License

[MIT](http://opensource.org/licenses/MIT)
