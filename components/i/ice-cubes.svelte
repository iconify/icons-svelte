<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dri8jfb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dri8jfb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ice-cubes" {...props}></Icon>
