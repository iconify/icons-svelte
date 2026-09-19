<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y21a7pbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y21a7pbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-018" {...props}></Icon>
