<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vlkwl-34d.css';
import '../../css/o/oy6a688zn.css';
import '../../css/k/k_lneb11t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vlkwl-34d"/><path class="oy6a688zn wm-a"/><path class="k_lneb11t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:archive-duo" {...props}></Icon>
