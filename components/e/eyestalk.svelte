<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl26o3b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tl26o3b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eyestalk" {...props}></Icon>
