<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/s-xqkdb4c.css';
import '../../css/h/hp7pw7bcp.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/h/hpmsss4bu.css';
import '../../css/s/skk29hbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="s-xqkdb4c wm-deco"/><path class="hp7pw7bcp wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="hpmsss4bu wm-k"/><path class="skk29hbed wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:drone-blueprint" {...props}></Icon>
