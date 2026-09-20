<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3x1ghdje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m3x1ghdje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pathfinder-square-union-remix" {...props}></Icon>
