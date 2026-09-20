<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x__8amb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x__8amb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:camera-video-off-2" {...props}></Icon>
