<!-- This file is auto-generated. DO NOT EDIT.                               -->

# Variables

<!-- BEGIN CONTENT -->

ZetaSQL specifies the syntax for the variable statements `SET` and
`UNSET`.

## VARIABLE TYPES

There are two primary variable types: runtime variables and query parameters.
Each can be set and unset with the `SET` and `UNSET` commands.
Additionally, query parameters are prefixed with a single @ symbol.

The variable names must be valid sql [identifiers][link-to-sql-identifiers].

## SET
Sets a variable.

```
SET runtime_variable = constant_value;
SET @query_parameter = constant_value;
```

## UNSET
Unsets a variable.

```
UNSET runtime_variable;
UNSET @query_parameter;
```

[link-to-sql-identifiers]: https://github.com/google/zetasql/blob/master/docs/lexical#identifiers

<!-- END CONTENT -->

