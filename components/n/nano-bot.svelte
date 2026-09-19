<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7ffal8nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k7ffal8nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nano-bot" {...props}></Icon>
