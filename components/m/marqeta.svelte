<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s79cvv-0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":220.93,"height":131.94};
const content = `<defs><symbol id="SVG6W14HcPs" viewBox="0 0 220.93 131.94"><path class="s79cvv-0n"/></symbol></defs><use width="220.93" height="131.94" href="#SVG6W14HcPs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:marqeta" {...props}></Icon>
