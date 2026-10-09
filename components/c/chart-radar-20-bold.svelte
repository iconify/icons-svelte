<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybysmhbdr.css';
import '../../css/u/un3d4_cir.css';
import '../../css/z/z2j4_3b3x.css';
import '../../css/i/iyzh_ybqf.css';
import '../../css/h/hw-gycbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ybysmhbdr"/><path class="un3d4_cir"/><path class="z2j4_3b3x"/><path class="iyzh_ybqf"/><path class="hw-gycbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-radar-20-bold" {...props}></Icon>
