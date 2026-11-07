<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c37ble74i.css';
import '../../css/t/tnz_2pl9f.css';
import '../../css/u/up4-ovb9f.css';
import '../../css/h/ht6mdpbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c37ble74i"/><path class="tnz_2pl9f"/><path class="up4-ovb9f"/><path class="ht6mdpbgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cup-hot-linear" {...props}></Icon>
