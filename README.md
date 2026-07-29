# Tessera Development Repository

> 🚧 **Development Branch** - main development repository for Tessera

## About Tessera

Tessera splits, processes and recomposes large images into tiles.

## 🔧 Development Status

This repository is under active development. Many features are TODO.

### 🔴 High Priority TODOs

- Core functionality is still being implemented across modules.

### 📝 Complete TODO List

- [ ] **tessera/filters/color.py:2** - clamp values to valid range after gamma
- [ ] **tessera/filters/color.py:3** - add per-channel adjustment support
- [ ] **tessera/filters/color.py:7** - use CLAHE for local contrast
- [ ] **tessera/tiling/merger.py:2** - blend seams between adjacent tiles
- [ ] **tessera/tiling/splitter.py:2** - support overlapping tile margins
- [ ] **tessera/tiling/splitter.py:3** - preserve geotiff metadata per tile

## 🤝 Contributing

1. Pick a TODO item from the list above
2. Implement the functionality
3. Update this README when TODOs are completed
