<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mah77fbvh.css';
import '../../css/t/tgcis5bxj.css';
import '../../css/y/yvh9lfbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mah77fbvh"/><path class="tgcis5bxj"/><path class="yvh9lfbdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-15-seconds-back-broken" {...props}></Icon>
