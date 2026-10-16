<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o640wlber.css';
import '../../css/w/woh0b19bt.css';
import '../../css/p/puz5jibvr.css';
import '../../css/n/nq5_p_bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o640wlber"/><path class="woh0b19bt"/><path class="puz5jibvr"/><path class="nq5_p_bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electrolyser-alert-20" {...props}></Icon>
