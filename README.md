# awesome-academic-drawio

# Awesome Academic Drawio

This repository replicates figures from top CS conferences and journals (IEEE, ACM, etc.) by providing editable, combinable diagram elements using Draw.io. Feel free to mix and match diagram elements to create improved visuals based on these.

## Table of Diagrams

| Paper | Conference/Journal & Year | Preview Image | File Path |
| ----- | ------------------------- | ------------- | --------- |
| [Paper Title](https://example.com) | IEEE TMC 2025 | ![Preview](papers/IEEE_2023_PaperID/figure.png) | [](/papers/IEEE_2023_PaperID/figure.drawio) |

Contributions that also link to excellent external drawing script repositories (e.g., Python scripts for advanced line-styles) are welcome.


## Folder Structure & Naming Conventions

- **/papers**  
  Each paper gets its own folder named in the format: `<Author><Year><ShortTitle><Journal/Conference>`, e.g. `ouyang2025mwrs`

  Each folder should include:
  - `figure.drawio` (editable source file)
  - `figure.png` (exported image preview)
  - (Optional) `README.md` with replication notes and metadata (links to the elements, say, [Freepic](https://www.freepik.com/) or [iconfont](https://www.iconfont.cn/))

*Note: GitHub doesn’t natively render `.drawio` files. Export images (PNG/SVG) for previews and use Draw.io integrations (like VS Code plugins) for editing.*

## Contributing

1. **Fork** the repository and create a branch for your contribution.
2. Follow the folder structure and naming guidelines.
3. Update the main README (or the dedicated table file) with your entry:
   - **Paper:** Title with link to the original paper.
   - **Conference/Journal & Year:** e.g., IEEE, 2023.
   - **Preview Image:** Link or embedded image.
   - **File Path:** Location of your diagram file.
4. Open a **Pull Request** with your changes.