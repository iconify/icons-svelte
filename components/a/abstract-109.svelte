<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3d09_w4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3d09_w4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-109" {...props}></Icon>
