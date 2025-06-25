# GitHub Models Workflow Analyzer

This directory contains configuration and documentation for the GitHub Models Workflow Analyzer system.

## 🎯 Purpose
The analyzer uses GitHub Models to predict workflow failures before they occur, saving time and resources by:
- Analyzing workflow files for potential issues
- Predicting success/failure with confidence scores
- Automatically canceling high-risk workflows
- Creating detailed issue reports with solutions
- Providing improvement recommendations

## 📁 Files
- `settings.json`: Main configuration file
- `README.md`: This documentation file

## ⚙️ Configuration
Edit `settings.json` to customize:
- Model selection and thresholds
- Risk level handling
- Excluded workflows
- Notification settings
- Analysis rules

## 🔧 Usage
The analyzer runs automatically on all workflows. Manual analysis can be triggered via workflow dispatch.

## 📊 Reports
Analysis results are available in:
- GitHub Issues (for predicted failures)
- Job summaries
- Uploaded artifacts
- PR comments (when applicable)

## 🛠️ Troubleshooting
If the analyzer isn't working:
1. Check GitHub Models API access
2. Verify repository permissions
3. Review workflow logs
4. Check configuration settings
