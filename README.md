# docker-swift-swiftlint-ruby
Docker images pre-built with [Swift](https://hub.docker.com/_/swift), [SwiftLint](https://github.com/realm/SwiftLint) and [Ruby](https://hub.docker.com/_/ruby).

## Version Matrix
For a full list of supported tags, refer [here](https://hub.docker.com/r/zaimramlan/swift-swiftlint-ruby/tags).

| Swift            | SwiftLint | Ruby    | Image Tag | Latest   |
|------------------|-----------|---------|-----------|----------|
| `5.2.4`<br>`5.2` | `0.39.2`  | `2.5.1` | `1.0.0`   | `latest` |

### Notes
- For compatibility with GitHub Actions, `Git` is reinstalled with `2.28.0`
- For ease of use, `Bundler v2.1.4` is pre-installed

## Motivations
- There isn't a straightforward way to install SwiftLint on Linux-based machines
- Existing Swift/SwiftLint docker images does not include Ruby (ie. can't use SwiftLint with Fastlane since it depends on Ruby)

## Contributions
Contributions via pull requests to improve the images are welcomed :)

## License
MIT
