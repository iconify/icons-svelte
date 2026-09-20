<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f-e2_lmrw.css';
import '../../css/n/n1_ykhn3f.css';
import '../../css/d/d20-0wyrx.css';
import '../../css/p/pq0e-etnf.css';
import '../../css/a/a0l-fdc8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f-e2_lmrw"/><path class="n1_ykhn3f"/><path class="d20-0wyrx"/><path class="pq0e-etnf"/><path class="a0l-fdc8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diploma-verified-linear" {...props}></Icon>
