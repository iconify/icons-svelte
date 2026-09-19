<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhc7mbtcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rhc7mbtcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:puzzle-piece-stroke-12" {...props}></Icon>
