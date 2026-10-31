<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rgqrr6scr.css';
import '../../css/l/l69tgy0if.css';
import '../../css/r/rmhlesbhl.css';
import '../../css/m/mti5rsbna.css';
import '../../css/u/u7l_q6bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rgqrr6scr wm-k"/><path class="l69tgy0if wm-shine"/><path class="rmhlesbhl wm-shine"/><path class="mti5rsbna wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:file-code" {...props}></Icon>
