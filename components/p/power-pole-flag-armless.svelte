<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgj3sr5dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mgj3sr5dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-flag-armless" {...props}></Icon>
