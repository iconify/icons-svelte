<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp1vgjbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGYOh97vgA" viewBox="0 0 99.5 70.9"><path class="wp1vgjbpl"/></symbol></defs><use width="99.5" height="70.9" href="#SVGYOh97vgA" transform="matrix(1.5 0 0 1.51 181.49 202.35)"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:fahrenheit" {...props}></Icon>
