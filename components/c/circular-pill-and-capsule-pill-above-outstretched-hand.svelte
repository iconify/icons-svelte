<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r07kyrbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r07kyrbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circular-pill-and-capsule-pill-above-outstretched-hand" {...props}></Icon>
