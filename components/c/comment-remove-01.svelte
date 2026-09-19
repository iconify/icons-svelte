<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n4ed50vxc.css';
import '../../css/w/wl_e0fb9e.css';
import '../../css/e/ewavw_btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n4ed50vxc"/><path class="wl_e0fb9e"/><path class="ewavw_btk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:comment-remove-01" {...props}></Icon>
