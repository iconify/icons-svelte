<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/a1k5gcctw.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/p/p6qte910m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="a1k5gcctw wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="p6qte910m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:radar-blueprint" {...props}></Icon>
