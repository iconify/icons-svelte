<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t95jodbbz.css';
import '../../css/i/i_s471zxc.css';
import '../../css/o/of-bm4x6d.css';
import '../../css/h/hz8sthhkd.css';
import '../../css/t/tl04nibly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t95jodbbz"/><path class="i_s471zxc wm-k"/><path class="of-bm4x6d wm-a"/><path class="hz8sthhkd wm-k"/><path class="tl04nibly wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:home-sketch" {...props}></Icon>
