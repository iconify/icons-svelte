<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc_w27bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hc_w27bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-storm" {...props}></Icon>
