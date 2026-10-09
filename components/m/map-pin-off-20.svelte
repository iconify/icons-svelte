<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds3wm4rom.css';
import '../../css/o/oh4-_7byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ds3wm4rom"/><path class="oh4-_7byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-off-20" {...props}></Icon>
