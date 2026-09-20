<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/ej_5n-b7k.css';
import '../../css/s/s17kxubxz.css';
import '../../css/u/u00ey8bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ej_5n-b7k"/><path class="s17kxubxz"/><circle class="u00ey8bps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:letter-unread-broken" {...props}></Icon>
