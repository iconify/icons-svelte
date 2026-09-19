<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c056y0bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c056y0bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-down-stroke-16" {...props}></Icon>
