<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyz6g2bdx.css';
import '../../css/f/fad7f9tkf.css';
import '../../css/w/wmo2g_b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tyz6g2bdx"/><path class="fad7f9tkf"/><path class="wmo2g_b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-20-bold" {...props}></Icon>
