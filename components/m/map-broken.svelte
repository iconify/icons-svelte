<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hj0xdxema.css';
import '../../css/h/hco13obdp.css';
import '../../css/h/h4fzukbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hj0xdxema"/><path class="hco13obdp"/><path class="h4fzukbso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-broken" {...props}></Icon>
