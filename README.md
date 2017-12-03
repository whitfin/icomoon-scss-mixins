# icomoon-scss-mixins

Simple SCSS mixins to enable working with [IcoMoon](https://icomoon.io/app) icon sets in a little more performant way, whilst also being easier to use.

### Installation

This module is on npm, so feel free to grab from there:

```shell
$ npm i icomoon-scss-mixins
```

### Examples

```scss
// import the mixins to your project SCSS setup
@import '../node_modules/icomoon-scss-mixins/scss/mixins.scss';

// define the name of your font, the path to your font, and the icons
@include icomoon('my-fonts', '../fonts/my-fonts', (
  arrow-right: "\e900",
  arrow-left: "\e901"
  // etc...
))
```

The path to your font should be the path to the icomoon resources (eot, svg, ttf, woff), just without any of the extensions provided (as they'll be loaded automatically).
