<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jmbz2vb9o.css';
import '../../css/z/zlsqrnbma.css';
import '../../css/h/hurexej9d.css';
import '../../css/t/t-at26brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jmbz2vb9o"/><path class="wm-k zlsqrnbma"/><path class="hurexej9d wm-k"/><path class="t-at26brw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-sketch" {...props}></Icon>
