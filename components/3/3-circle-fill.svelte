<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydg3l3bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ydg3l3bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:3-circle-fill" {...props}></Icon>
