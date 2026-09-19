<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc4c0sbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cc4c0sbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:health-potion" {...props}></Icon>
