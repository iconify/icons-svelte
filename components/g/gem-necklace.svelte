<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmc13sb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xmc13sb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gem-necklace" {...props}></Icon>
