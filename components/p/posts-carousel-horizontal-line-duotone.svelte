<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l5l1hedvi.css';
import '../../css/m/m-nft4g9k.css';
import '../../css/c/cx-7pstvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l5l1hedvi"/><path class="m-nft4g9k"/><path class="cx-7pstvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-horizontal-line-duotone" {...props}></Icon>
