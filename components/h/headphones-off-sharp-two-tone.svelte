<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/b/bty7mpj8n.css';
import '../../css/k/keaa46byq.css';
import '../../css/i/itmzxabip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bty7mpj8n"/><path class="keaa46byq"/><path class="itmzxabip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:headphones-off-sharp-two-tone" {...props}></Icon>
