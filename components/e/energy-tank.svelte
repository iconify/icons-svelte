<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsuf0h8wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bsuf0h8wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:energy-tank" {...props}></Icon>
