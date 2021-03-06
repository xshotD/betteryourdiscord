# BetterYourDiscord
The Discord CSS overhaul.

# Current code includes:

- Opacity
- "Frosted glass" look
- Images by Unsplash as your background

# Installing

If you'd like to install BYD, you can import it into a CSS file, using rawgit's service.
(Nornal GitHub raw URLs do NOT work!)

```css
@import url(https://rawgit.com/xshotD/betteryourdiscord/master/src/byd.css);
```

If you're a developer and want to build (with minify and autoprefixer) you're in luck too!

Simply run these commands:

```
npm install --only=dev
gulp
```

You can find the minified/autoprefixed CSS in the `out` folder.

Further, you can test the gulp code with `npm test`.

# Credits

```
| Author    | Parts            | Copyright           |
-----------------------------------------------------
| BoxOfFlex | transparent base | (c) 2016 BoxOfFlex |
| TripingPC | frosted glass    | (c) 2017 TripingPC |
| Google    | fonts            | (c) 2017 Google    |
| Unsplash  | backgrounds      | None.              |
| xshotD    | the rest         | (c) 2017 S Stewart |
```
