# ember-import-snippets

This extension contains helpful Ember snippets based on the new import syntax post-[RFC176](https://github.com/ember-cli/ember-rfc176-data). This is a work-in-progress and additional imports will be included.

## Currently Supported Imports
### Getters/Setters

Input | Result
--- | ---
`imp e getset` | `import { get, getProperties, set, setProperties } from '@ember/object';`
`imp e get` | `import { get, getProperties } from '@ember/object';`
`imp e set` | `import { set, setProperties } from '@ember/object';`

### Inject as Service

Input | Result
--- | ---
`imp e service` | `import { inject as service } from '@ember/service';`

### Computeds

Input | Result
--- | ---
`imp e computed all` | `import { alias, readOnly, and, bool } from '@ember/object/computed';`
`imp e computed` | `import { computed } from '@ember/object';`
`imp e computed readonly` | `import { readOnly } from '@ember/object/computed';`
`imp e computed alias` | `import { alias } from '@ember/object/computed';`

### Run Loop

Input | Result
--- | ---
`imp e runloop` | `import { bind, later, run } from '@ember/runloop';`

### ember-concurrency

Input | Result
--- | ---
`imp e concurrency` | `import { task, timeout } from 'ember-concurrency';;`
`imp e concurrency task` | `import { task } from 'ember-concurrency';`
`imp e concurrency timeout` | `import { timeout } from 'ember-concurrency';`
