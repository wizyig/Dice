# Dice (🎲)

Dice is an exploration operator for Pi³XI.

It opens candidate paths. It does not prove them.

## Purpose

🎲 represents exploration.

It is neither observation nor evidence.

A dice result may suggest.

A dice result does not prove.

## State Space

```text
🎲
  = exploration

BaguaMap
  = classification

Record
  = observation

Diff
  = relation
```

Dice explores a state space defined by its execution environment.

The execution environment determines:

- permissions
- constraints
- validation rules

Dice itself does not enumerate every prohibition.

## Transition Rule

```text
🎲
  ↓
Observation
  ↓
Record
```

Exploration may transition into observation.

Only observations may become Canonical Records.

Unobserved exploration may be discarded.

Discarding exploration does not affect Canonical Records or Diffs.

## Observation

LLM outputs are exploration artifacts by default.

They are not automatically:

- observations
- records
- evidence

```text
Canonical Record = README
Supporting Evidence = assets/
```

Expected assets:

```text
assets/state-map.png
assets/dice-layout.png
assets/session-example.png
```

## Example Run

### Audit layer

```text
🎲
  -> candidate repository structure

Observation
  -> repository tree

Record
  -> Canonical Record
```

### Workspace exploration

```text
🎲
  -> possible architectures

BaguaMap
  -> classification

Record
  -> observed implementation
```

### Repository planning

Observed repository:

```text
README.md
LICENSE
```

🎲 result:

```text
audit/
tests/
schemas/
```

Status:

```text
candidate path
```

Not a Record.

## License

MIT
