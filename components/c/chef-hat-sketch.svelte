<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yv00_jbgb.css';
import '../../css/m/m-1en5bcn.css';
import '../../css/t/t8rssobqf.css';
import '../../css/g/g2_80jbow.css';
import '../../css/o/os7a8djmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="yv00_jbgb"/><path class="m-1en5bcn wm-k"/><path class="t8rssobqf wm-a"/><path class="g2_80jbow wm-k"/><path class="os7a8djmh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chef-hat-sketch" {...props}></Icon>
