public class WNieva {

    // ----------------------------------------------------------
    // 👋 About me
    // ----------------------------------------------------------
    public void presentation() {
        System.out.println("👋 Hi, I'm @wnieva");
        System.out.println("👀 System Engineer | Developer | CISO | Founder of Version Uno SpA (Chile)");
        System.out.println("🌱 Currently learning Cybersecurity (Kali Linux, pentesting & privacy)");
        System.out.println("🔭 Building commercial solutions focused on automation and data analysis");
        System.out.println("📫 william.nieva@versionuno.cl");
        System.out.println("🌐 wnieva.versionuno.cl");
    }

    // ----------------------------------------------------------
    // 🧠 Core stack
    // ----------------------------------------------------------
    public List<String> stack() {
        return List.of(
            // Mobile & Web
            "Flutter",
            "Angular (LTS)",
            "React",
            // Backend & Microservices
            "NestJS",
            "NodeJS",
            "Java",
            "Python",
            "REST APIs",
            // Data
            "PostgreSQL",
            "MariaDB",
            // Infra
            "Linux (VPS deployment & administration)",
            "Git (branching strategies, hooks & security guards)"
        );
    }

    // ----------------------------------------------------------
    // 🚀 Projects & ventures
    // ----------------------------------------------------------
    public Map<String, String> projects() {
        return Map.of(
            "Version Uno SpA",
            "Software studio: technical & commercial proposals, development and digital products",
            "Consulta Protegida",
            "Digital product: Ley 21.719 compliance kit for psychologists (Chile)",
            "Refactoriza",
            "Refactoring & technical debt service: legacy code modernization for SMEs",
            "Computer Vision for Agroindustry",
            "Automated bin-counting and consumption reconciliation systems for fruit packing",
            "Job-search automation",
            "PegaFlow: automated job-search platform for Chile/LATAM",
            "Documentation automation",
            "Claude-powered skill that generates user manuals and technical docs"
        );
    }

    // ----------------------------------------------------------
    // 🛡️ Security mindset
    // ----------------------------------------------------------
    public void security() {
        System.out.println("🔐 CISO perspective: security by design, not as an afterthought");
        System.out.println("🧪 Home lab: Kali Linux for pentesting and anonymity research");
        System.out.println("🪝 Personal 3-layer security system across all repos:");
        System.out.println("   → global git hook, Claude Code hook, deployment guard agent");
    }

    // ----------------------------------------------------------
    // 🏗️ Infrastructure
    // ----------------------------------------------------------
    public void infrastructure() {
        System.out.println("🖥️  2 VPS: one for databases, one for deploying microservices");
        System.out.println("📦 Microservices architecture with NestJS, Spring Boot and REST APIs");
        System.out.println("🗄️  PostgreSQL & MariaDB as primary data stores");
    }

    // ----------------------------------------------------------
    // 🎯 Current focus & goals
    // ----------------------------------------------------------
    public void currentFocus() {
        System.out.println("📱 Building a React mobile web app for a school (parents, students, teachers)");
        System.out.println("💼 Open to remote/hybrid opportunities in Chile, LATAM & international");
        System.out.println("🤝 Interested in: automation, data analysis, cybersecurity, AI-assisted dev");
    }

    // ----------------------------------------------------------
    // 💡 Philosophy
    // ----------------------------------------------------------
    public void philosophy() {
        System.out.println("⚡ Efficient, scalable and low-cost solutions first");
        System.out.println("📈 Business value from day one: every feature should earn its keep");
        System.out.println("🧹 Clean code, clear architecture, and technical debt paid down early");
    }

    // ----------------------------------------------------------
    // 🤝 Let's connect
    // ----------------------------------------------------------
    public void contact() {
        System.out.println("💬 Got a project, a legacy system to refactor, or an idea to automate?");
        System.out.println("📩 Write me: william.nieva@versionuno.cl");
    }

    // ----------------------------------------------------------
    // ▶️ Entry point
    // ----------------------------------------------------------
    public static void main(String[] args) {
        WNieva william = new WNieva();
        william.presentation();
        william.stack();
        william.projects();
        william.security();
        william.infrastructure();
        william.currentFocus();
        william.philosophy();
        william.contact();
    }
}
