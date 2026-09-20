<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxifirbbl.css';
import '../../css/r/ryxm1nv_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxifirbbl"/><path class="ryxm1nv_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:e-commerce-touch-buy-bold" {...props}></Icon>
