<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpf8b5hfv.css';
import '../../css/p/pinl4fblr.css';
import '../../css/x/xk9q94btg.css';
import '../../css/f/fghgm1b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lpf8b5hfv"/><path class="pinl4fblr"/><path class="xk9q94btg"/><path class="fghgm1b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:globe-outline" {...props}></Icon>
