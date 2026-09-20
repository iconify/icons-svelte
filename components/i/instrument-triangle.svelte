<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt-f31bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt-f31bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:instrument-triangle" {...props}></Icon>
