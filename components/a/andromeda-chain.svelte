<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9kbgubgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c9kbgubgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:andromeda-chain" {...props}></Icon>
