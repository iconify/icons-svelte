<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rwzkv6b2g.css';
import '../../css/u/uqhik9b3f.css';
import '../../css/d/d-03ckbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rwzkv6b2g"/><path class="uqhik9b3f"/><path class="d-03ckbqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:history-2-broken" {...props}></Icon>
