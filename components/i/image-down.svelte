<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/ddghpn2-o.css';
import '../../css/m/mh06cqblr.css';
import '../../css/a/axf4zcygn.css';
import '../../css/v/vbqbujntv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="ddghpn2-o"/><path class="mh06cqblr"/><path class="axf4zcygn"/><path class="vbqbujntv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:image-down" {...props}></Icon>
