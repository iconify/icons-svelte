<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tnfby2q5d.css';
import '../../css/p/pu97ujszu.css';
import '../../css/d/d7egxzbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tnfby2q5d"/><path class="pu97ujszu"/><path class="d7egxzbrr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-charge-minimalistic-broken" {...props}></Icon>
