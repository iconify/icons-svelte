<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/spin9_bwp.css';
import '../../css/y/yxesn464s.css';
import '../../css/f/fcx47xikt.css';
import '../../css/l/lqw4xwbkq.css';
import '../../css/o/otcq8cr0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="spin9_bwp"/><path class="wm-k yxesn464s"/><path class="fcx47xikt wm-a"/><path class="lqw4xwbkq wm-k"/><path class="otcq8cr0s wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crown-sketch" {...props}></Icon>
