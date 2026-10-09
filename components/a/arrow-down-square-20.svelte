<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxp0_ibgn.css';
import '../../css/v/vr_lhqmel.css';
import '../../css/z/zr7ldxbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qxp0_ibgn"/><path class="vr_lhqmel"/><path class="zr7ldxbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-square-20" {...props}></Icon>
