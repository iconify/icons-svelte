<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gma_0sbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gma_0sbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-triangle" {...props}></Icon>
