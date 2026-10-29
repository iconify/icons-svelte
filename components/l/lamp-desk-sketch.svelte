<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nadl88edg.css';
import '../../css/e/e-6vslbun.css';
import '../../css/k/k-9auubar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nadl88edg"/><path class="e-6vslbun"/><path class="k-9auubar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lamp-desk-sketch" {...props}></Icon>
