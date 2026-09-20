<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wlfgbb32o.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/n/n92ediatx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wlfgbb32o"/><circle class="h_tsn8bxt"/><path class="n92ediatx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-broken" {...props}></Icon>
