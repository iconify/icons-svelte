<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb1-qkblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tb1-qkblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ghost-ally" {...props}></Icon>
