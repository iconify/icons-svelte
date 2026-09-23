<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/x5kq9ej_d.css';
import '../../css/z/zr5m9kbwl.css';
import '../../css/x/x95g1kbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x5kq9ej_d"/><path class="zr5m9kbwl"/><path class="x95g1kbnv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:eraser-sparkles-sharp-duotone" {...props}></Icon>
