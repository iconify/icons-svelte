<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlj03gb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nlj03gb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ninja-armor" {...props}></Icon>
