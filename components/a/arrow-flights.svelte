<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5t4rgbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f5t4rgbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arrow-flights" {...props}></Icon>
