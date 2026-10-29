<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/mx878-b0u.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/g/gmt-k0r6b.css';
import '../../css/p/pzj6afbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="mx878-b0u wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="gmt-k0r6b wm-k"/><path class="pzj6afbau wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cpu-blueprint" {...props}></Icon>
