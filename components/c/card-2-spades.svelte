<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy954vbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uy954vbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-2-spades" {...props}></Icon>
