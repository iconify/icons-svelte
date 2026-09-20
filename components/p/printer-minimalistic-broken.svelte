<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mmq6zvbgf.css';
import '../../css/k/k8mwp_zry.css';
import '../../css/f/fg9hpm71u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mmq6zvbgf"/><path class="k8mwp_zry"/><path class="fg9hpm71u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-minimalistic-broken" {...props}></Icon>
