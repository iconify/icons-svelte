<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnnahnb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="pnnahnb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:buy-n-large" {...props}></Icon>
