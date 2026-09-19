<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/frli32bnn.css';
import '../../css/l/ljd34hyaq.css';
import '../../css/p/p2wr0qbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="frli32bnn"/><path class="ljd34hyaq"/><path class="p2wr0qbvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:location-10" {...props}></Icon>
