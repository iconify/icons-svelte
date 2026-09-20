<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rp-rncc0y.css';
import '../../css/m/mt58vcclw.css';
import '../../css/h/h_mjq-bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rp-rncc0y"/><path class="mt58vcclw"/><path clip-rule="evenodd" class="h_mjq-bfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:draw-compass-filled" {...props}></Icon>
