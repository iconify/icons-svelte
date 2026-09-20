<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew-n46vse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ew-n46vse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:maze" {...props}></Icon>
