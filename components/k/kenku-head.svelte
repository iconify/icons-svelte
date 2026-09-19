<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll8x3e97m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ll8x3e97m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kenku-head" {...props}></Icon>
