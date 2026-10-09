<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu-s-mrny.css';
import '../../css/y/ypecetwke.css';
import '../../css/w/wqngztpuq.css';
import '../../css/t/ts68x3biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gu-s-mrny"/><path class="ypecetwke"/><path class="wqngztpuq"/><path class="ts68x3biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-candlestick-48" {...props}></Icon>
