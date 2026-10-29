<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/flvjb4byi.css';
import '../../css/c/ce4_fwbku.css';
import '../../css/v/v4zv_uo1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="flvjb4byi wm-a"/><path class="ce4_fwbku"/><path class="v4zv_uo1i wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:printer" {...props}></Icon>
