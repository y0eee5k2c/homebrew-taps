# homebrew-taps

A small tap with formulae I use on my own machines.

## Why

I wanted something I could read in one sitting and vendor into a project if needed.

## Install

```bash
pip install homebrew-taps
```

## Usage

```python
from homebrew_taps import homebrewTaps

result = homebrewTaps("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
