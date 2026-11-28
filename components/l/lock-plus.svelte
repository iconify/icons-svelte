<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i71m81irf.css';
import '../../css/d/didesjkug.css';
import '../../css/n/n5j9s2_ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i71m81irf"/><path class="didesjkug"/><path class="n5j9s2_ic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lock-plus" {...props}></Icon>
