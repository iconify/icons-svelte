<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqz63qbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqz63qbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:half-tornado" {...props}></Icon>
