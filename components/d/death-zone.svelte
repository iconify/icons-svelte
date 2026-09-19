<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl0n1cb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bl0n1cb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:death-zone" {...props}></Icon>
