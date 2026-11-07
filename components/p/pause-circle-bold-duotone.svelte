<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpv5vhdla.css';
import '../../css/r/rycrv8brk.css';
import '../../css/d/dkcg6hhbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="rycrv8brk"/><path class="dkcg6hhbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pause-circle-bold-duotone" {...props}></Icon>
