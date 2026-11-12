<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt02fdobb.css';
import '../../css/b/bbhq1vbgh.css';
import '../../css/l/lt995w-hc.css';
import '../../css/j/jmm_6pidh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dt02fdobb"/><path class="bbhq1vbgh"/><path class="lt995w-hc"/><path class="jmm_6pidh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peanut" {...props}></Icon>
