<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgmz4lbip.css';
import '../../css/v/vaynj5-ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pgmz4lbip"/><path class="vaynj5-ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-microphone-1" {...props}></Icon>
