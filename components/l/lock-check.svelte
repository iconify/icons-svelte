<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i71m81irf.css';
import '../../css/d/didesjkug.css';
import '../../css/h/h_j87acvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i71m81irf"/><path class="didesjkug"/><path class="h_j87acvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lock-check" {...props}></Icon>
