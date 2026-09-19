<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkyvt1b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hkyvt1b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-065" {...props}></Icon>
