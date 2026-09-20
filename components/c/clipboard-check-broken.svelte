<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wyvt0nbum.css';
import '../../css/n/ndq0ugbyy.css';
import '../../css/m/m390b8qby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wyvt0nbum"/><path class="ndq0ugbyy"/><path class="m390b8qby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-check-broken" {...props}></Icon>
