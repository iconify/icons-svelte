<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu98br64n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bu98br64n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-080" {...props}></Icon>
