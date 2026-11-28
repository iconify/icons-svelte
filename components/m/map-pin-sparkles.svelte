<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bae6gablz.css';
import '../../css/m/m4d6n2bve.css';
import '../../css/v/vtm2u7_cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bae6gablz"/><path class="m4d6n2bve"/><circle class="vtm2u7_cv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:map-pin-sparkles" {...props}></Icon>
