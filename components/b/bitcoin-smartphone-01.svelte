<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bs2p8bb3r.css';
import '../../css/w/watrmtrxt.css';
import '../../css/t/td99tubxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bs2p8bb3r"/><path class="watrmtrxt"/><path class="td99tubxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin-smartphone-01" {...props}></Icon>
