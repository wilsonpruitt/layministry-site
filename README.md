# layministry-site

The public pitch/overview microsite for reactivating Lay Servant Ministries
in Rio Texas — **layministry.wrootlabs.com**. A shareable artifact for
talking to the DS, conference lay leader, and prospective teaching pastors,
built ahead of any dates or faculty being confirmed.

Astro, static output, no framework beyond that. Design tokens copied from
the `wroot-labs-design` skill (Fen & Ink palette, EB Garamond + Inter) —
`public/styles/tokens.css` (do not hand-edit; re-copy from the skill if the
brand tokens change) + `public/styles/site.css` (this site's layout).

Two pages: `/` (the pitch — why now, the three-rung ladder, the proposal,
current status) and `/course` (the five-session schedule in detail).

Planning docs and status tracking live in `~/laity` (this repo is just the
built artifact). See `~/laity/README.md` for where this fits in the larger
plan.

## Dev

```
pnpm install
pnpm dev
pnpm build
```
