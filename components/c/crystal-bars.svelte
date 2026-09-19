<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpd1w5bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpd1w5bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crystal-bars" {...props}></Icon>
