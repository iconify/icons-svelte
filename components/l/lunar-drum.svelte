<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mymtxlbif.css';
import '../../css/q/ql50srbzb.css';
import '../../css/s/sla9ccbde.css';
import '../../css/u/uoju-z_9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mymtxlbif"/><path class="ql50srbzb"/><path class="sla9ccbde wm-s"/><path class="uoju-z_9h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lunar-drum" {...props}></Icon>
