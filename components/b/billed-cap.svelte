<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx3vdt36c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vx3vdt36c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:billed-cap" {...props}></Icon>
