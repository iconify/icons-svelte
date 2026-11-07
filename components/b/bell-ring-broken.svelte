<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dv5-5hz_c.css';
import '../../css/x/xdy3g3xzv.css';
import '../../css/t/tihjbyfia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dv5-5hz_c"/><path class="xdy3g3xzv"/><path class="tihjbyfia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-ring-broken" {...props}></Icon>
