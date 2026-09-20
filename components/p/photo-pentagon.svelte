<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tpglke3oj.css';
import '../../css/z/zztr2aboi.css';
import '../../css/y/yvm4rmb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tpglke3oj"/><path class="zztr2aboi"/><path class="yvm4rmb-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-pentagon" {...props}></Icon>
