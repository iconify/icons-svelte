<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji-4rabzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ji-4rabzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clothes" {...props}></Icon>
