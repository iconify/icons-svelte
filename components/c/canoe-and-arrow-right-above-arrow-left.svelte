<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg_1uzbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fg_1uzbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-and-arrow-right-above-arrow-left" {...props}></Icon>
