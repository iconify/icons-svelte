<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/v/vqm0_dtme.css';
import '../../css/c/ciss-jbrv.css';
import '../../css/f/fe1ld0bgr.css';
import '../../css/f/fltmthbdi.css';
import '../../css/m/mnqpjmj2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="vqm0_dtme"/><path class="ciss-jbrv"/><path class="fe1ld0bgr"/><path class="fltmthbdi"/><path class="mnqpjmj2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:crosshair" {...props}></Icon>
