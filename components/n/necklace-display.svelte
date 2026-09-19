<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3j-4zoln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3j-4zoln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:necklace-display" {...props}></Icon>
