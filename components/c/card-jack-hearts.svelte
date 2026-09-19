<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyjtk83dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eyjtk83dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-jack-hearts" {...props}></Icon>
