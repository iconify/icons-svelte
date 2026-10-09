<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwehzwmcr.css';
import '../../css/i/idt7ziwvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vwehzwmcr"/><path class="idt7ziwvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:compliance-20-bold" {...props}></Icon>
