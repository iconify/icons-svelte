<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p73hu3bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="p73hu3bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-speed-1x" {...props}></Icon>
