# Week 6 Assignment — Safe Tools & Error Handling

- `safe_tools.py` — Contains functions that safely handle division, number conversion, and dictionary field lookup.
- `unbreakable.py` — Demonstrates why an `if` check alone cannot safely handle invalid number input.

The `if` check cannot catch `abc` on its own because `abc` is a string, and the error happens when Python tries to convert it using `int()`. The `int()` conversion raises a `ValueError`, which must be handled using `try` and `except`.