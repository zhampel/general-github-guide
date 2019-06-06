# general-github-guide
Guide to using GitHub in collaborative environments.

Slides providing overview of contributing with teams to GitHub repos.

Online slides can be found [here](https://zhampel.github.io/general-github-guide/#/).

## Usage

The slides for this talk can be generated locally via:

```bash
virtualenv -p /usr/local/bin/python3 venv
source venv/bin/activate
pip install -r requirements.txt

cp notebooks/general_github_guide_slides.ipynb general_github_guide_slides.ipynb
jupyter nbconvert general_github_guide_slides.ipynb --to slides --post serve --template output_toggle.tpl --SlidesExporter.reveal_transition=none --SlidesExporter.reveal_scroll=True --SlidesExporter.reveal_theme=serif
```
