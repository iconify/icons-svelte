<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6yv8ac1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6yv8ac1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:google-play-fill" {...props}></Icon>
