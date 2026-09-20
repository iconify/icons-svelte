<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/q9oyscbnt.css';
import '../../css/z/zia4plbis.css';
import '../../css/v/vshazwbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q9oyscbnt"/><path class="zia4plbis"/><path class="vshazwbdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panorama-line-duotone" {...props}></Icon>
