# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Context

This is the **AI Independence** site, one of six interconnected Hugo-based websites in the hugo-sites-knowledge-base multi-site system. The site focuses on technical solutions for escaping AI surveillance and control, targeting privacy advocates, tech workers, and security professionals.

## Site-Specific Details

**Theme**: Terminal (cyberpunk/hacker aesthetic)
**Content Focus**: Technical tutorials, surveillance countermeasures, privacy tools, anonymous computing
**Target Audience**: Privacy advocates, security professionals, tech workers
**Publishing Schedule**: 2 posts/week (Tuesday: technical tutorials, Friday: countermeasures)

## Essential Commands

```bash
# Development server with drafts
hugo server -D

# Build site for production
hugo

# Create new post
hugo new posts/your-post-title.md

# Create new post with content subdirectory structure
hugo new content/posts/your-post-title.md

# Navigate to parent directory for multi-site operations
cd ..

# Update all sites in parent directory
../update-sites.sh

# Create new post using interactive script
../new-post.sh
```

## Directory Structure

```
ai-independence/
├── archetypes/          # Content templates
├── content/
│   ├── posts/          # Blog posts
│   └── about.md        # About page
├── hugo.toml           # Site configuration
├── themes/
│   └── terminal/       # Terminal theme files
└── static/             # Static assets (images, etc.)
```

## Site Configuration

**Base URL**: https://ai-independence.com/
**Theme**: Terminal theme with blue color scheme
**Menu Structure**: privacy/, surveillance/, local-ai/, tools/, about.txt
**Logo**: "ai-free:~$" (terminal prompt style)

## Content Strategy

**Core Topics**:
- Local AI setup (private ChatGPT alternatives)
- Surveillance countermeasures (facial recognition blocking)
- Privacy tools (VPNs, encrypted communication)
- Anonymous computing (Tor, Linux, degoogling)
- Anti-tracking techniques

**Content Categories** (matches menu structure):
- privacy
- surveillance  
- local-ai
- tools

## Multi-Site Integration

This site is part of a larger ecosystem:
- **Parent Directory**: Contains 6 Hugo sites with shared scripts
- **Cross-Promotion**: Sites reference each other for audience growth
- **Shared Resources**: Common scripts for content creation and site management
- **Revenue Focus**: High-value affiliates and premium digital products

## Key Files in Parent Directory

- `MASTER-SITE-GUIDE.md`: Business strategy and revenue projections
- `content-workflow.md`: Publishing schedules and content creation process
- `update-sites.sh`: Git automation for all sites
- `new-post.sh`: Interactive post creation tool

## Content Creation Workflow

1. Use `../new-post.sh` for interactive post creation
2. Or manually: `hugo new posts/post-title.md`
3. Edit content in `content/posts/`
4. Test locally: `hugo server -D`
5. Build for production: `hugo`

## Theme Customization

The Terminal theme provides:
- Hacker/cyberpunk aesthetic
- Terminal-style navigation
- Blue color scheme
- Responsive design
- Syntax highlighting for code blocks

## Deployment

Sites deploy via Cloudflare Pages:
- Build command: `hugo`
- Publish directory: `public/`
- Framework preset: Hugo
- Cloudflare provides unified ecosystem with Pages, DNS, and CDN
- Cost optimization: Single provider for all sites

## Revenue Model

**Target**: $5K+ Year 1
**Monetization**:
- High-value affiliate programs (System76, GPU retailers, VPN services)
- Premium digital products ($67-$197 price range)
- Technical consulting ($300-500/hour)
- Focus on privacy hardware and software sales