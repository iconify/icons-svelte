<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6z4ynbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f6z4ynbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-donau-1-level" {...props}></Icon>
