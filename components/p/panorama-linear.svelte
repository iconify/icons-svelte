<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gneet3b3q.css';
import '../../css/t/t2cylssnp.css';
import '../../css/i/i1h42obmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gneet3b3q"/><path class="t2cylssnp"/><path class="i1h42obmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panorama-linear" {...props}></Icon>
