# Change Log

All notable changes to the "ukiyo" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Ukiyo 0.1.0 - 0.6.0] - 2019-12-26

- Initial release

## [Ukiyo 0.7.0] - 2020-01-18

### Added

- Better support for React, with 'classNames', 'key', and other ancillary keywords colored orange (#f9af8f)

### Changed

- Fixed object colons to match the white (#d3d3d3) of other syntactical elements
- Equals sign in React now displaying as yellow to match keywords (#d0cd7b)

### Removed

- Dashed red (#eb7f7f) underline for unused code has been removed because it was distracting when coupled with the default eslint warning underline

## [Ukiyo 0.8.0] - 2020-02-19

### Changed

- Fixed the look of global object methods like .length to be orange (#f9af8f) in .tsx files and match .js conventions
- Fixed the look of support type primitives in .ts and .tsx files to be orange and match the display of types elsewhere
