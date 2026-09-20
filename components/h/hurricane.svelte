<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv-71ub5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pv-71ub5e"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="1440 256 256; 0 256 256"/></path>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:hurricane" {...props}></Icon>
