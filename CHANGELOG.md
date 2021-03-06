# Change Log

All notable changes to this code base will be documented in this file, in every released version.

## 0.1.8 (2020-12-28)

- Add `examples` to project to demonstrate usage.
- Add `DEFAULT_SCHEMA_CLASS` explicitly for `coreapi` schema generation. See `README.md` for details.

## 0.1.7 (2018-06-01)

- Add `DISCOVERY_READ_ONLY` setting to optionally specify whether or not the API should be read-only.
- Add testing and tox to the project build.
- Add `CHANGELOG.md` for tracking and documenting notable changes to the code base.
- Add `.editorconfig`, `setup.cfg`, and `Makefile` for easier contribution and build tooling.

## 0.1.6 (2018-04-20)

- Add functionality to silently ignore tables without a primary key column.
- Add `DISCOVERY_PROFILE_NAME` setting to specify database profile.
- Add `DISCOVERY_INCLUDE` setting to optionally specify which tables to include.
- Add `DISCOVERY_EXCLUDE` setting to optionally specify which tables to ignore.
