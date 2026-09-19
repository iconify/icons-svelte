<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuzo8w5dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":384};
const content = `<path class="wuzo8w5dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:paypal-alt" {...props}></Icon>
