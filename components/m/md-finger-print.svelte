<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh20y2bau.css';
import '../../css/v/vf1c710_a.css';
import '../../css/l/lhow-8b0x.css';
import '../../css/m/mge_w5m3i.css';
import '../../css/k/klnn7_i_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yh20y2bau"/><path class="vf1c710_a"/><path class="lhow-8b0x"/><path class="mge_w5m3i"/><path class="klnn7_i_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-finger-print" {...props}></Icon>
