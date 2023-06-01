# Guidebook iOS

## Project Setup
All project setup [references are here](spec/Setup)

### Git Stuff
We did a massive directory restructuring to match the Xcode project structure. 
Before this, all files were in a single dir. But we've lost the files changes history. 
You can inspect a single file by using `--follow` flag:
```
git log --follow --pretty=oneline <file_here>
```

### Dependencies
See [how we use Cocoapods for private pods](spec/Setup)

## Code Style
[Code Style Guidelines for ObjC and Swift](spec/CodeStyleGuideline)

## Modules documentation
All modules documentation [is here](spec/Documentation)

### Diagrams
Docs that need diagrams, we should use:
- We use https://sequencediagram.org to edit and render sequence diagrams
- Also https://app.diagrams.net to other diagram types

Remember to include a `.svg/.png` **AND** a `.txt` so the diagram can be edited.

## Patterns
[Here](spec/Patterns) the patterns we use.

### Env vars (how to point to Staging)
We use environment variables from our schemes, [more here](spec/Patterns/EnvVars)

### Error Logging
See [all about Error Logging](spec/Patterns/ErrorLogging)

## Testing
### Testing branded apps
See [how we to test branded app locally](spec/HowTo/TestBranded)

### Testing SSO apps
[Test SSO](spec/HowTo/Test-SSO.md)
