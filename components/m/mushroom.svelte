<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrerf5bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mrerf5bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mushroom" {...props}></Icon>
