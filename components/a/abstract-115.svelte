<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t95d3yb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t95d3yb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-115" {...props}></Icon>
