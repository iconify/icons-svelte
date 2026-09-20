<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-qr39bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-qr39bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:page-layout-marginals" {...props}></Icon>
