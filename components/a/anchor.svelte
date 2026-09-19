<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stcan_o_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="stcan_o_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:anchor" {...props}></Icon>
