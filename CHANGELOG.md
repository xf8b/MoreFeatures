# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added:
- Added changelog

### Changed
- Changed hunger command syntax
- Made blocks that were supposed to be flammable, flammable.

### Fixed
- Fixed [#7](https://github.com/xf8b/MoreFeatures/issues/7) (Effects applied by enchantments are still present after the armor has broken)

### Removed:
- Removed access transformer

## [1.15.2-1.0.0-beta1] - 2020-6-3
### Fixed:
- Fixed [#6](https://github.com/xf8b/MoreFeatures/issues/6) (Getting null tag causes crashes)

## [1.15.2-1.0.0-alpha6] - 2020-6-3
### Added:
- Added config
- Added curse enchantments
- Added new blocks
- Added new effect
- Added "armor" (if you call a mask armor, but it had to be registered as a ArmorItem)
- Added asbestos to generation
- Added corrupted tools
- Added crops
- Added commands

### Changed:
- Changed MCP mappings version
- Changed lapis armor to have local tick counters instead of using the TickCounter class
- Changed .gitignore to include ._ files
- Changed code to be formatted correctly

### Fixed:
- Fixed corrupted sword not changing attack damage and speed

## [1.15.2-1.0.0-alpha5] - 2020-5-25
### Added:
- Added new foods
- Added new trees
- Added enchantments

### Changed:
- Changed how the corrupted sword gets a random attack damage and speed
- Changed README.md to have stats about the mod on CurseForge
- Changed the issue templates to use "Versions" instead of "Desktop"
- Changed MCP mappings version
- Changed some items to be compostable

### Fixed:
- Fixed [#3](https://github.com/xf8b/MoreFeatures/issues/3) (Items in the MoreFeatures item group do not appear)
- Fixed [#4](https://github.com/xf8b/MoreFeatures/issues/4) (Fire Retardant enchantment doesn't work)

### Removed:
- Removed most of the item descriptions

## [1.15.2-1.0.0-alpha4] - 2020-5-17
### Added:
- Added coal armor
- Added lapis armor
- Added emerald armor

### Changed:
- Changed issue template to have correct spelling and be more easy to read
- Changed ore generation to be ran using DeferredWorkQueue
- Changed the locations of tools/items to be in packages (e.g. instead of all tools being in the tools package, it would be tools.sapphire)

### Fixed:
- Fixed [#2](https://github.com/xf8b/MoreFeatures/issues/2) (Obsidian armor causes fall damage death on crouch)

## [1.15.2-1.0.0-alpha3] - 2020-5-16
### Added:
- Added update.json
- Added obsidian armor

### Changed:
- Changed README.md to have the correct version number
- Changed the Forge version to 31.2.0
- Changed build.gradle to use values in gradle.properties

## [1.15.2-1.0.0-alpha2] - 2020-5-15
### Added:
- Added issue templates
- Added sapphire tool textures
- Added ore generation
- Added corrupted sword
- Added item descriptions
- Added item recipes
- Added loot tables
- Added smelting recipe
- Added sapphire ore

### Changed:
- Changed .gitignore to include .DS_Store
- Changed README.md to have the logo correctly display and have download links
- Changed the package name from com.github.xf8b.morefeatures to io.github.xf8b.morefeatures
- Changed MCP mappings version

### Fixed:
- Fixed [#1](https://github.com/xf8b/MoreFeatures/issues/1) (Flipped axe recipe doesn't work)

## [1.15.2-1.0.0-alpha1] - 2020-5-8
### Added: 
- Added sapphire armor
- Added sapphire tools
- Added sapphire
- Added sapphire block

[Unreleased]: https://github.com/xf8b/MoreFeatures/compare/v1.15.2-1.0.0-beta1...1.15.2-development
[1.15.2-1.0.0-beta1]: https://github.com/xf8b/MoreFeatures/compare/v1.15.2-1.0.0-beta1...v1.15.2-1.0.0-alpha6
[1.15.2-1.0.0-alpha6]: https://github.com/xf8b/MoreFeatures/compare/v1.15.2-1.0.0-alpha6...v1.15.2-1.0.0-alpha5
[1.15.2-1.0.0-alpha5]: https://github.com/xf8b/MoreFeatures/compare/v1.15.2-1.0.0-alpha5...v1.15.2-1.0.0-alpha4
[1.15.2-1.0.0-alpha4]: https://github.com/xf8b/MoreFeatures/compare/v1.15.2-1.0.0-alpha4...v1.15.2-1.0.0-alpha3
[1.15.2-1.0.0-alpha3]: https://github.com/xf8b/MoreFeatures/compare/v1.15.2-1.0.0-alpha3...v1.15.2-1.0.0-alpha2
[1.15.2-1.0.0-alpha2]: https://github.com/xf8b/MoreFeatures/compare/v1.15.2-1.0.0-alpha2...v1.15.2-1.0.0-alpha1
[1.15.2-1.0.0-alpha1]: https://github.com/xf8b/MoreFeatures/compare/192620cdc55ad2400d5ef5300c5c2b39a47276dd...v1.15.2-1.0.0-alpha1