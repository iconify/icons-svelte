<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdy47f24p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sdy47f24p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chess-knight" {...props}></Icon>
