<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/felal2qtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="felal2qtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:carnival-mask" {...props}></Icon>
