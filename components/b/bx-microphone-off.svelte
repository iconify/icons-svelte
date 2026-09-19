<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua71p0bsg.css';
import '../../css/l/lnske1bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua71p0bsg"/><path class="lnske1bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-microphone-off" {...props}></Icon>
