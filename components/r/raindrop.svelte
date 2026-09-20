<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4f5e1b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGoQRCkbPD" viewBox="0 0 175 260.9"><path class="i4f5e1b5a"><animateTransform attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="scale" values="1 1; 1 .9; 1 1"/></path></symbol></defs><use width="175" height="260.9" href="#SVGoQRCkbPD" transform="translate(168.5 122.62)"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:raindrop" {...props}></Icon>
