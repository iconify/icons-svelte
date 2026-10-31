<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ay2i4ly5t.css';
import '../../css/p/p_umfntdc.css';
import '../../css/x/xlxw1xe_o.css';
import '../../css/r/rjufokmvr.css';
import '../../css/u/u7l_q6bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ay2i4ly5t wm-k"/><path class="p_umfntdc wm-shine"/><path class="wm-shine xlxw1xe_o"/><path class="rjufokmvr wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:file-json" {...props}></Icon>
