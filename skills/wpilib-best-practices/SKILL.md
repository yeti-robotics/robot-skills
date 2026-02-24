---
name: wpilib-best-practices
description: >
  WPILib and FRC robot programming best practices, design patterns, and code guidance for Java.
  Use when writing, reviewing, or explaining WPILib robot code—command-based project structure,
  subsystems, autonomous routines, RobotContainer layout, command definition patterns (inline,
  factory, subclass), motor/sensor integration, or Constants organization.
---

# WPILib Best Practices

WPILib best practices span multiple domains. Load only the reference(s) relevant to the current task.

## References

| Domain | Reference | When to load |
| ------ | --------- | ------------ |
| Command-based architecture | [references/command-based.md](references/command-based.md) | Project structure, `Robot`/`RobotContainer` layout, command definition patterns (inline vs factory vs subclass), autonomous routines, subsystem organization, `Constants` class |

## Quick Navigation

- **"How do I structure my command-based project?"** → [command-based.md](references/command-based.md) (Project Structure)
- **"Should I use a factory method or a Command subclass?"** → [command-based.md](references/command-based.md) (Pattern Selection)
- **"Where do subsystems and button bindings go?"** → [command-based.md](references/command-based.md) (RobotContainer)
- **"How do I handle multi-subsystem commands without circular deps?"** → [command-based.md](references/command-based.md) (Static Command Factories)
- **"How do I compose sequences and parallel groups?"** → [command-based.md](references/command-based.md) (Subclassing Command Groups)
