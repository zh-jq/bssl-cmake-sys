# bssl-cmake-sys

A BoringSSL rust binding based on [bssl-sys](https://github.com/google/boringssl/tree/master/rust/bssl-sys) crate.

The vendored BoringSSL code is incorperated to the CMake build system, which means:
- you need to install cmake
- golang is not required

## Release Support

The version will always be 0.1.YYYYMMDD.

We will pull in changes from BoringSSL main branch weekly, but it's not guranteed.

