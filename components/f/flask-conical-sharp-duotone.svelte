<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/t/tvbb9gb-d.css';
import '../../css/r/r1a_d_bgc.css';
import '../../css/d/dx93_50hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tvbb9gb-d"/><path class="r1a_d_bgc"/><path class="dx93_50hj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flask-conical-sharp-duotone" {...props}></Icon>
