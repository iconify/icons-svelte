<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwbp2gbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vwbp2gbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrows-move" {...props}></Icon>
