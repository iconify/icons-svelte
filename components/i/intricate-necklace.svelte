<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5reyiz2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u5reyiz2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:intricate-necklace" {...props}></Icon>
