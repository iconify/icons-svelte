<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt24h6bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt24h6bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cart-off" {...props}></Icon>
