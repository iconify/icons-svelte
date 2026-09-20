<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v32ch_s6q.css';
import '../../css/r/rt9zs7bvl.css';
import '../../css/p/p3ifo4qzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v32ch_s6q"/><path class="rt9zs7bvl"/><path class="p3ifo4qzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:eye-off" {...props}></Icon>
