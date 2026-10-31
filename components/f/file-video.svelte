<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ir2usgbdh.css';
import '../../css/o/owz0w1w-e.css';
import '../../css/p/p0d_zwbuc.css';
import '../../css/c/c34fvcchc.css';
import '../../css/u/u7l_q6bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ir2usgbdh wm-k"/><path class="owz0w1w-e wm-shine"/><path class="p0d_zwbuc wm-shine"/><path class="c34fvcchc wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:file-video" {...props}></Icon>
