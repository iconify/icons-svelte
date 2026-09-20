<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zb8-kubni.css';
import '../../css/w/wq2ys5qgg.css';
import '../../css/x/x10wpcb7q.css';
import '../../css/u/uq4x3pb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zb8-kubni"/><path class="wq2ys5qgg"/><path class="x10wpcb7q"/><path class="uq4x3pb0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:file-upload" {...props}></Icon>
