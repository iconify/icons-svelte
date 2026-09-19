<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj9x6h2zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aj9x6h2zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:blood" {...props}></Icon>
