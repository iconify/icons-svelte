<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/w_xe7g5xk.css';
import '../../css/a/aczsw8qlb.css';
import '../../css/f/fswci7foh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w_xe7g5xk"/><path class="aczsw8qlb"/><path class="fswci7foh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-scatter-bubble-sparkles-sharp-two-tone" {...props}></Icon>
