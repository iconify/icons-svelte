<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2oge1bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p2oge1bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:puppet" {...props}></Icon>
