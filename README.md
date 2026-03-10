# nanobot-feishu-send

Send images, files, audio, and video to Feishu using nanobot's `message` tool.

## Quick Start

```json
{
  "content": "给你发图",
  "media": ["/path/to/photo.png"]
}
```

## Notes

- Use local file paths only.
- Put file paths in `media`, not `content`.
- If you only have a URL, download it first.
