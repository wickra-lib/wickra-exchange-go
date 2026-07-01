# wickra-exchange-go

The standalone Go module mirror of
[`wickra-exchange`](https://github.com/wickra-lib/wickra-exchange) — streaming-native,
unified connectivity for the ten largest crypto exchanges, with paper and replay
simulators that share the same API.

```bash
go get github.com/wickra-lib/wickra-exchange-go
```

This repository is a **derived artifact**: its contents are assembled and pushed
automatically from `wickra-exchange`'s `bindings/go` by the release pipeline on
every tagged release (the Go source, the vendored C ABI header, and the prebuilt
native libraries under `lib/<goos>_<goarch>/`). Do not edit it by hand — open
changes against `wickra-exchange` instead.

Licensed under `MIT OR Apache-2.0`.
