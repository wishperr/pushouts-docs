# Task: Implement Progressive Health System

## Objective
Create the health system with progressive health loss when players are outside the arena.

## Requirements
- Base health of 100 points
- Initial health loss rate of 1 per second
- Accelerated loss (1/250ms) after 60 seconds
- Clear visual health indicators
- Out-of-bounds detection

## Technical Details
- Health state tracking
- Timer system for loss rate changes
- Boundary detection system
- Health UI implementation
- Death state handling

## Acceptance Criteria
- [ ] Health starts at 100
- [ ] Health loss begins immediately outside arena
- [ ] Loss rate increases correctly at 60s
- [ ] Health bar/indicator is clearly visible
- [ ] Player elimination works at 0 health
- [ ] Health state syncs across network

## Dependencies
- Arena boundaries
- Basic player state system
- UI framework

## Estimated Time
- 2-3 days

## Priority
P0 - Core Mechanic