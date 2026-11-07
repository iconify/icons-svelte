<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/km0klhbji.css';
import '../../css/p/pzh9jhb6y.css';
import '../../css/d/dfwvprboi.css';
import '../../css/r/rsrcios1h.css';
import '../../css/v/vn59_jbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="km0klhbji"/><path class="pzh9jhb6y"/><path class="dfwvprboi"/><path class="rsrcios1h"/><path class="vn59_jbgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:backpack-broken" {...props}></Icon>
