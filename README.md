> ## This module is DEPRECATED
> This module has been moved to the monorepo [wocss](https://github.com/wocss/wocss/tree/master/packages/settings.breakpoints#readme) (and renamed to `@wocss/settings-breakpoints`)

# BREAKPOINTS

> Setting

The `wocss-settings-breakpoints` module contains media queries breakpoints `variables` for the framework's modules and [sass-mq](https://github.com/sass-mq/sass-mq). Feel free to reassign these variables.

Install using npm:

```sh
$ npm install wocss-settings-breakpoints --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you should import this module writing:

```scss
@import '~wocss-settings-breakpoints';
```

### Variables

#### `$wocss-breakpoints`

| Key | Value |
|---------------|-------|
| `'mobile'` | `320px` |
| `'tablet'` | `768px` |
| `'laptop'` | `1024px` |
