# Cache Desk changelog

## 1.1.0 — 27 September 2026

Made by **Wunet**. Freeware; implementation source remains private.

- Compact interface with a visible version number and an About tab covering the maker, requirements, behavior, and license.
- Read-only thumbnail gallery for supported PNG, JPEG, and BMP entries, with paging, larger previews, cache details, reload, and cancellation. Pictures are not exported. Cache IDs do not establish original paths or deletion status; index databases and raw or unsupported payloads are not pictures the gallery can display.
- File review, category folders, file-location access, explicit item selection, and confirmation before permanent deletion. Categories cover thumbnail caches, temporary files at least 24 hours old, recent shortcuts, and Jump Lists including pins.
- Administrator mode extends cleanup to accessible registered local profiles, Windows Temp, and Prefetch caches. It uses normal Windows UAC approval; it does not force credential entry or collect passwords.
- Saved Wi-Fi profile removal with the current account's scope, plus machine profiles in administrator mode. Windows shortcuts cover clipboard history, devices, storage cleanup, and Explorer options.
- Cancellation, scan limits, locked-file skipping, and checks for files changed or replaced since scanning.

Validation: **100 automated checks passed** (17 cleanup, 51 thumbnail-reader, 32 UI). A generated 54-picture gallery was manually verified across pages. Live-cache metadata identified 147 supported PNG/JPEG entries without decoding personal pictures. UAC credential entry and destructive cleanup of real user data were not tested.
