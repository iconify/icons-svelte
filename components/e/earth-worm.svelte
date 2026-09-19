<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oodhp_big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oodhp_big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:earth-worm" {...props}></Icon>
