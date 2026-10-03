<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnk3vlb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnk3vlb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:qbittorrent" {...props}></Icon>
