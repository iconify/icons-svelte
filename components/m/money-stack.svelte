<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khm5-lbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="khm5-lbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:money-stack" {...props}></Icon>
