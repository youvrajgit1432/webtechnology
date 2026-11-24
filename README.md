# Web Technology Practice

Keep teacher-assigned work separate from your own practice:

- `college-tasks` — do the assigned task yourself during class and keep the teacher's requirements here.
- `home-practice` — write a new, similar exercise yourself at home. Try not to copy your class file; use it to check what you understand.

Both folders have the same topic areas:

- `01-html-css`
- `02-javascript`
- `03-json`
- `04-ajax`
- `05-php`
- `06-integrated-practice`

Save each exercise in the relevant topic folder, using a clear name such as `task-01.html` or `practice-01.html`. The new areas are empty so you can write all code yourself. Existing top-level topic folders were left unchanged to preserve your current files.

## Running your work

For basic HTML, CSS, and JavaScript, open an HTML file in a browser and refresh after saving. AJAX requests generally need the page served over HTTP rather than opened as a `file://` URL.

PHP was not available when this workspace was set up. After installing PHP, open a terminal at this workspace's root and run one of these commands to serve that area:

```powershell
php -S localhost:8000 -t .\college-tasks\05-php
```

```powershell
php -S localhost:8000 -t .\home-practice\05-php
```

Then visit `http://localhost:8000`. For AJAX work, use the same commands with `04-ajax` in place of `05-php`. Stop the server with `Ctrl+C`.
