<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/irgi_rb-g.css';
import '../../css/k/kwapx1btc.css';
import '../../css/u/uniftz_yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="irgi_rb-g"/><path class="kwapx1btc"/><path class="uniftz_yv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:armchair-line-duotone" {...props}></Icon>
