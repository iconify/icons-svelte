<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt-98jkjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt-98jkjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cctv-off-line" {...props}></Icon>
