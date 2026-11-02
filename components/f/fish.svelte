<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/t/tq4iw64sa.css';
import '../../css/h/h_q57btlx.css';
import '../../css/i/io9aq7bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="tq4iw64sa"/><path class="h_q57btlx"/><path class="io9aq7bmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:fish" {...props}></Icon>
