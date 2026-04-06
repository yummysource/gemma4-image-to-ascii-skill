---
---
name: image-to-ascii
description: Convert an image to ASCII art.
---

# Image to ASCII Art

## Instructions

When the user shares an image and asks for ASCII art:

1. Get the image as a base64 data URL
2. Call the run_js tool with script name `index.html` and data:
   {"imageData": "<full base64 data URL>", "width": 80, "mode": "simple"}
3. For block/pixel style, use mode "block". For wider output, increase width.
4. Display the returned result directly.

If no image provided, ask the user to share one first.
