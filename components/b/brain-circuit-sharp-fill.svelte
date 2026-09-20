<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/frc_m5boq.css';
import '../../css/p/pg13u4ygs.css';
import '../../css/e/ei48vjbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="frc_m5boq"/><path class="pg13u4ygs"/><path class="ei48vjbzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brain-circuit-sharp-fill" {...props}></Icon>
