# Do I Have Enough Time?

A short interactive tool that helps prospective students work out whether they
have enough free time in a typical week to take on a specific module or
course.

This version is set up for **Evidence-Informed Teaching and Professional
Practice in Tertiary Education** (100 hours over 15 weeks), but the numbers
at the top of the `<script>` block in `index.html` can be changed to retarget
it at any module:

```js
var MODULE_TOTAL_HOURS = 100;
var MODULE_WEEKS = 15;
```

## Deploying with GitHub Pages

1. Create a new **public** repository on GitHub (e.g. `enough-time-tool`).
2. Upload `index.html` to the root of that repository (drag-and-drop on
   github.com works fine, or `git push` if you're comfortable with the
   command line).
3. In the repository, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`. Save.
5. GitHub will publish the page at:
   `https://<your-username>.github.io/<repository-name>/`
   This can take a minute or two the first time.

No build step, server, or dependencies are needed — it's a single static
HTML file with everything (CSS and JS) inline.

## Licence / attribution

Adapted from the [Student Success Toolbox](https://github.com/studentsuccesstoolbox/StudentSuccessToolbox)
(Dublin City University, IT Sligo, Maynooth University and Dundalk Institute
of Technology), licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Attribution is
retained in the footer of the page — please keep it there if you redistribute
or adapt further.
