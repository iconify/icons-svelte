<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnl6s70sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dnl6s70sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pteruges" {...props}></Icon>
