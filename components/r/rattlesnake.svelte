<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blg0q0b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="blg0q0b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rattlesnake" {...props}></Icon>
