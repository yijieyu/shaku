# Change Log

All notable changes to Shaku are documented in this file using the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## [1.4.0] - 2018-11-09

### Added

* The `Collection::remove()` method has been added

### Fixed

* The `Collection` template contained a hard-coded class name for the `contains()` method

## [1.3.0] - 2018-11-08

### Added

* The `Collection::contains()` and `Collection::isEmpty()` methods have been added

### Changed

* The `Collection::items()` method has been renamed to `Collection::toArray()`

## [1.2.0] - 2018-11-08

### Changed

* The constructor for immutable `Collection` classes is now `private`

## [1.1.0] - 2018-11-07

### Added

* The generated `Collection` object now implements the `Countable` interface

## 1.0.0 - 2018-11-07

* Initial release

[1.4.0]: https://github.com/sebastianbergmann/shaku/compare/1.3.0...1.4.0
[1.3.0]: https://github.com/sebastianbergmann/shaku/compare/1.2.0...1.3.0
[1.2.0]: https://github.com/sebastianbergmann/shaku/compare/1.1.0...1.2.0
[1.1.0]: https://github.com/sebastianbergmann/shaku/compare/1.0.0...1.1.0
