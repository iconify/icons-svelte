<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/lux4zt8kc.css';
import '../../css/a/aikblhfzb.css';
import '../../css/p/pia5khlmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lux4zt8kc"/><path class="aikblhfzb"/><path class="pia5khlmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:orientation-image-landscape-to-potrait" {...props}></Icon>
