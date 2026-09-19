<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr7ginidu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rr7ginidu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:death-star" {...props}></Icon>
