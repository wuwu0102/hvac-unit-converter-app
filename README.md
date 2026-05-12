# HVAC Unit Converter App

iOS and Android app wrapper for HVAC Unit Converter.

## Architecture

- `hvac-unit-converter` → Production web version
- `hvac-unit-converter-app` → Native iOS / Android packaging layer

## Goals

- Keep production website stable
- Separate native mobile packaging from web logic
- Use Capacitor for iOS and Android builds
- Avoid modifying production calculation logic directly in the mobile repo

## Planned Structure

- Capacitor iOS project
- Capacitor Android project
- GitHub Actions for APK / iOS artifact generation
- App icons and splash screens
- TestFlight and Play Store deployment flow
