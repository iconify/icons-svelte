<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r_kmw_yut.css';
import '../../css/z/zv97pxbdl.css';
import '../../css/p/ptvu1u_4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r_kmw_yut"/><path class="zv97pxbdl"/><circle class="ptvu1u_4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:point-on-map-line-duotone" {...props}></Icon>
