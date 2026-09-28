# libgpg-error

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/l/libgpg-error.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/libgpg-error-1.61-h54a6638_2.conda | `b69606451dfce168990dd40324e52daf981472511788d412ce78664760d3889f` | conda-forge libgpg-error 1.61 h54a6638_2 (LGPL-2.1-only) |

## Command

```
.agents/tools/repack/repack.py \
    --name libgpg-error \
    --version 1.61 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/libgpg-error-1.61-h54a6638_2.conda#b69606451dfce168990dd40324e52daf981472511788d412ce78664760d3889f \
    --host 'lib/libgpg-error.so*' \
    --require lib/libgpg-error.so.0
```

