# Recommendation Letter — Xingwei Qu

LaTeX source for a recommendation letter written by **Jie Fu (Fujie)** in support of **Xingwei Qu**'s application to Anthropic.

## Files

- `main.tex` — the letter source (academic / formal style, A4, 11pt Palatino).

## Build locally

```bash
pdflatex main.tex
```

## Open in Overleaf

1. Go to <https://www.overleaf.com/project>.
2. Click **New Project → Import from GitHub**.
3. Select this repository.
4. Set `main.tex` as the main document.

## Customize letterhead

Edit the placeholder macros near the top of `main.tex`:

```latex
\newcommand{\senderName}{Jie Fu, Ph.D.}
\newcommand{\senderTitle}{Researcher}
\newcommand{\senderAffiliation}{[Your Affiliation]}
\newcommand{\senderEmail}{[Your Email]}
\newcommand{\senderPhone}{[Your Phone]}
\newcommand{\senderWebsite}{[Your Website / ORCID]}
```
