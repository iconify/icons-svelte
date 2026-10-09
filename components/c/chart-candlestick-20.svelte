<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-p0xm3rr.css';
import '../../css/e/eb5j48vwt.css';
import '../../css/m/m3rdxrnyn.css';
import '../../css/n/ndjuxyb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-p0xm3rr"/><path class="eb5j48vwt"/><path class="m3rdxrnyn"/><path class="ndjuxyb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-candlestick-20" {...props}></Icon>
