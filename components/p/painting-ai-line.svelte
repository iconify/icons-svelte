<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0dut0-fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0dut0-fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:painting-ai-line" {...props}></Icon>
