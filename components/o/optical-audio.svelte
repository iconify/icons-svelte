<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtx3_bc3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtx3_bc3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:optical-audio" {...props}></Icon>
