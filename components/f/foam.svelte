<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0d3nx-bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y0d3nx-bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:foam" {...props}></Icon>
