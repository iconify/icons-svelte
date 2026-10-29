<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/g82uymb2s.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/n/nko2m3b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="g82uymb2s wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="nko2m3b8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-blueprint" {...props}></Icon>
