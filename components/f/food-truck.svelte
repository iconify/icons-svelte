<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cel9776qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cel9776qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:food-truck" {...props}></Icon>
