video2gif
=========

Convert a video file (mp4, mov, etc.) to a reasonable GIF.

Usage
-----

Download:
```
mkdir -p "$HOME/.local/bin"        # or anywhere else in your $PATH
curl -L "https://raw.githubusercontent.com/wookayin/video2gif/master/video2gif" > "$HOME/.local/bin/video2gif" \
  && chmod +x "$HOME/.local/bin/video2gif"
```

Requires ffmpeg.

```bash
$ video2gif foo.mp4
$ video2gif foo.mp4 foo.gif --scale 640
$ video2gif foo.mp4 foo.gif --fps 24 --scale 50%
```

References
----------

- http://blog.pkh.me/p/21-high-quality-gif-with-ffmpeg.html#usage


License
-------

MIT License (c) 2020 Jongwook Choi (@wookayin)
