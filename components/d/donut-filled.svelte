<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mita_xbuw.css';
import '../../css/r/r8_oqnbcm.css';
import '../../css/s/su1i-1q6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mita_xbuw"/><path class="r8_oqnbcm"/><path clip-rule="evenodd" class="su1i-1q6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:donut-filled" {...props}></Icon>
