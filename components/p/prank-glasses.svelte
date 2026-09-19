<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug1uhpbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ug1uhpbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:prank-glasses" {...props}></Icon>
