<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/d_pslabds.css';
import '../../css/o/oaibiac4l.css';
import '../../css/e/ei48vjbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d_pslabds"/><path class="oaibiac4l"/><path class="ei48vjbzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brain-circuit-sharp-two-tone" {...props}></Icon>
