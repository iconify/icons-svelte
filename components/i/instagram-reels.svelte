<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp935pb2i.css';
import '../../css/c/ca5grhk1u.css';
import '../../css/n/nw9d4_b1h.css';
import '../../css/y/yj7wg2bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVGRfIQhcUt" cx="256" cy="256" r="255.23" gradientUnits="userSpaceOnUse"><stop offset="0" class="sp935pb2i"/><stop offset=".1" class="sp935pb2i"/><stop offset=".5" class="ca5grhk1u"/><stop offset="1" class="nw9d4_b1h"/></radialGradient><path fill="url(#SVGRfIQhcUt)" class="yj7wg2bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:instagram-reels" {...props}></Icon>
