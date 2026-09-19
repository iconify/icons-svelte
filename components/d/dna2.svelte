<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixi6hl2_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixi6hl2_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dna2" {...props}></Icon>
