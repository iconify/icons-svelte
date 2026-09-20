<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xji5qxura.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xji5qxura"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-point-of-sale-outline" {...props}></Icon>
