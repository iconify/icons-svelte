<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3_ogq_yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3_ogq_yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:etsy-logo" {...props}></Icon>
