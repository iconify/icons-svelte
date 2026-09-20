<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k_8y6cbed.css';
import '../../css/p/pu97ujszu.css';
import '../../css/d/d7egxzbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k_8y6cbed"/><path class="pu97ujszu"/><path class="d7egxzbrr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-charge-broken" {...props}></Icon>
