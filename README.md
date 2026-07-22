# onboarding-test-starcatch

A tiny arcade test game for the YouTeacher desktop games platform: **Star Catch**.
Slide a basket to catch falling stars, dodge the bombs, survive as the sky speeds up.

This repo is **pure content** — a `frontend/` folder plus a `game.json` manifest. The shared
`game-shell` + packaging pipeline wrap it into signed mac/windows desktop apps and publish it
to the store on a `dev-v*` (dev) or `v*` (prod) tag.

```
onboarding-test-starcatch/
├── frontend/
│   ├── game.html   ← the game (single-file HTML canvas)
│   └── icon.png    ← app icon
└── game.json       ← name + store listing
```

See `game-shell/AUTHORING.md` for the full authoring guide.
