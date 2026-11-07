<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dirz042nc.css';
import '../../css/x/xdy3g3xzv.css';
import '../../css/t/tihjbyfia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dirz042nc"/><path class="xdy3g3xzv"/><path class="tihjbyfia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-off-broken" {...props}></Icon>
