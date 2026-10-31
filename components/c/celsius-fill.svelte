<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orexe2b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVG8c4FjcGg" viewBox="0 0 109.1 73.2"><path class="orexe2b-x"/></symbol></defs><use width="109.1" height="73.2" href="#SVG8c4FjcGg" transform="matrix(1.46 0 0 1.47 176.26 202.35)"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:celsius-fill" {...props}></Icon>
