<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ekfw6raai.css';
import '../../css/z/zuar5lbsy.css';
import '../../css/b/bhhd6db8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ekfw6raai wm-a"/><path class="wm-k zuar5lbsy"/><path class="bhhd6db8f wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-bar-decreasing-sketch" {...props}></Icon>
