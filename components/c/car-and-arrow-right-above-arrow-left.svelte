<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgbh2sbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rgbh2sbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-and-arrow-right-above-arrow-left" {...props}></Icon>
