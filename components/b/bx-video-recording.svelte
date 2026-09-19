<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xalk1bbvn.css';
import '../../css/r/r0ke4kbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xalk1bbvn"/><path class="r0ke4kbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-video-recording" {...props}></Icon>
