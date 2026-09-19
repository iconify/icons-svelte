<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y59_e3bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y59_e3bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:camera-off" {...props}></Icon>
