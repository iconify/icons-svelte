<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm-1pkbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wm-1pkbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:counterclockwise" {...props}></Icon>
