<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wghyucbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wghyucbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-1-level" {...props}></Icon>
