<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hs8rvvlxb.css';
import '../../css/f/fu7ml01dv.css';
import '../../css/a/avvl2tizt.css';
import '../../css/s/sbmqfhzny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hs8rvvlxb"/><path class="fu7ml01dv"/><path class="avvl2tizt"/><path class="sbmqfhzny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ranking-line-duotone" {...props}></Icon>
