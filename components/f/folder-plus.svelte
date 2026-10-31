<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oiuiv5blj.css';
import '../../css/s/shv3ws-ls.css';
import '../../css/i/i0hrabppd.css';
import '../../css/m/meelv53to.css';
import '../../css/r/rt9v9sb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oiuiv5blj wm-k"/><path class="shv3ws-ls wm-shine"/><path class="i0hrabppd wm-shine"/><path class="meelv53to wm-shine"/><path class="rt9v9sb0t wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:folder-plus" {...props}></Icon>
