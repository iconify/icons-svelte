<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wlgc_xbce.css';
import '../../css/t/tvvz7sbyy.css';
import '../../css/p/p51-u5b-l.css';
import '../../css/h/h3bpwcjgi.css';
import '../../css/u/u83h24b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wlgc_xbce wm-k"/><path class="tvvz7sbyy wm-a"/><path class="p51-u5b-l wm-shadow"/><path class="h3bpwcjgi wm-k"/><path class="u83h24b3i wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plane-landing-engrave" {...props}></Icon>
