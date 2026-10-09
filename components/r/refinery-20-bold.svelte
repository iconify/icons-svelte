<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-nxg9bwf.css';
import '../../css/u/u5r5zmbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-nxg9bwf"/><path class="u5r5zmbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refinery-20-bold" {...props}></Icon>
