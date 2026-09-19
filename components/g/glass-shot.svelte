<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm4x219yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bm4x219yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:glass-shot" {...props}></Icon>
