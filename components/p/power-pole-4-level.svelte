<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb93zrbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pb93zrbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-4-level" {...props}></Icon>
