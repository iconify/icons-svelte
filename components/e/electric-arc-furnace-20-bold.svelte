<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smlwvlmfy.css';
import '../../css/n/ntge0rvwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="smlwvlmfy"/><path class="ntge0rvwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-arc-furnace-20-bold" {...props}></Icon>
