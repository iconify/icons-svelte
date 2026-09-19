<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9no4pb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9no4pb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:half-heart" {...props}></Icon>
