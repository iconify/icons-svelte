<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/ckm4b1x8o.css';
import '../../css/y/y1ionlbid.css';
import '../../css/m/m-g3ie7bv.css';
import '../../css/a/aak1lpbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ckm4b1x8o"/><path class="y1ionlbid"/><path class="m-g3ie7bv"/><path class="aak1lpbyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:point-on-map-perspective-bold-duotone" {...props}></Icon>
