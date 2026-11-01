# Click-to-Create — Design

## Shared content and visual direction

- PDF, Web and Video are independently selected outputs. Ask once when formats are unspecified; honor an explicit selection. Share verified steps, sanitized screenshots, captions, numbering, dates and expected results across selected formats.
- Use a light background, one primary accent, readable Thai type, generous spacing and a strong visual focus per step. Reference videos guide style, not permission to reuse third-party logos or assets.
- Preserve screenshot context. Numbered callouts must not cover labels. Redact sensitive pixels before embedding; CSS overlays do not remove secrets. Label generated illustrations and simulated motion; they are not evidence of real UI behavior.

## PDF only when selected

- Give PDF its own readable page layout, with complete steps, captions and images. Do not require a reader to scroll, expand, play or run a website to access content.
- Choose orientation to keep Thai text and screenshot labels readable. Avoid cutting important content across pages, needless covers and shrinking an entire web page to fit.
- An internal HTML print source is allowed as an implementation detail; it does not require delivery of HTML or an interactive web guide. Deliver only requested formats.
- Render and visually inspect every PDF page. If content changes, rebuild and inspect affected pages. If PDF production fails, explain the missing PDF and agree on any alternative; do not silently substitute HTML.

## Web only when selected

- Default to a self-contained HTML guide with sanitized embedded images and local CSS/JavaScript. Reading and demonstration playback work offline. Opening the target site or sending an AI task may need a connection.
- Include step selection, previous/next, image enlargement, progress, keyboard navigation, pause/replay and reduced-motion support. No task execution on page load.
- Three controls: **เล่นสาธิต** plays documented step motion without changing the target application; **เปิดเว็บทำเอง** opens a verified safe entry URL; **ให้ AI ทำให้** dispatches a real task to the user's own authorized AI account and receives a task ID/status.
- Inspect integration support before implementing the AI control. Preserve receiver approval rules; do not invent universal desktop links or silently substitute copying a prompt. Do not create a shared owner-funded service, credentials, paid account or local service without authorization.
- Without a supported receiver, keep the control visibly **ยังไม่ได้เชื่อมต่อ AI** and explain the limitation. Distinguish disconnected, ready, submitting, accepted/running, completed, failed and unknown results when connected. Evidence from the receiver is required to report success; avoid duplicate submissions after an uncertain result and provide cancellation if supported.
- Opening HTML, hosting a website and connecting AI are distinct. Publish only to an authorized destination and sharing scope. Do not claim an uploaded Drive HTML file is a running website.
- A web demonstration does not require producing an MP4. Test navigation, demo, image controls and safe links; test actual AI dispatch only when configured and authorized.

## Video only when selected

- Create video directly from verified steps and available screenshots/recordings. PDF and Web are not prerequisites. Choose instructional vs showcase style from the request; ask if that distinction changes the result and is unknown.
- Inspect relevant sample frames/timing of reference videos. Reuse style and motion concepts without treating depicted controls as verified application behavior or reusing unlicensed assets.
- Make Thai captions readable with adequate display time; keep callouts aligned with the actual step. Share the agreed visual style with other selected formats.
- Agree on material format/duration/narration/music choices when absent and consequential. No added paid generation, synthetic voice, music or new service without authorization. A silent captioned draft is not a narrated finished video.
- Use available video authoring/rendering tools and their skills. If rendering is unavailable, identify any storyboard/composition as a draft and state that MP4 is missing; do not claim video delivery.
- Verify exported file duration, dimensions and playable video stream, inspect frames at transitions and important actions, and check captions/audio when included. Report sampled inspection as sampled inspection, not a full playback test.
