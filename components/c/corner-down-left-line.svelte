<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilj8trt6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilj8trt6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-down-left-line" {...props}></Icon>
