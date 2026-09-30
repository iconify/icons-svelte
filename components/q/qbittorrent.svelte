<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk3u05b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk3u05b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:qbittorrent" {...props}></Icon>
