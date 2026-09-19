<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j2fdhp6zb.css';
import '../../css/u/u7qllch4d.css';
import '../../css/g/g_ap0obtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j2fdhp6zb"/><path class="u7qllch4d"/><path class="g_ap0obtx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin-withdraw" {...props}></Icon>
