# Modified cpplint

## This is a modified version of cpplint for teaching CS courses.

The specific modifications are:

- Changing the _DEFAULT_FILTERS in cpplint.py to add the following filters:

```
_DEFAULT_FILTERS = [
    "-legal/copyright",
    "-whitespace/line_length",
    "-build/header_guard",
    "-build/namespaces",
    "-runtime/references",
    "-readability/todo",
    "-whitespace/tab",
]
```

