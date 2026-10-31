<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/k/kf64mebyu.css';
import '../../css/p/p8yrg0x8f.css';
import '../../css/p/p28w8bcvx.css';
import '../../css/w/wo89xnbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="kf64mebyu"/><path class="p8yrg0x8f wm-k"/><path class="p28w8bcvx wm-a"/><path class="wm-deco wo89xnbgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:microscope" {...props}></Icon>
