# redux-saga

## 1.1.4
### Patch Changes

- b07defe: Added warnings when using `take(channelOrPattern)` incorrectly with more than one parameter. It helps to surface problem with `take(ACTION_A, ACTION_B)` being used instead of `take([ACTION_A, ACTION_B])`.

- Updated dependencies [b07defe]
  - @redux-saga/core@1.1.4