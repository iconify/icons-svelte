<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p8ue_zwas.css';
import '../../css/d/d4rt0lb-l.css';
import '../../css/z/zc2m5bbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p8ue_zwas"/><path class="d4rt0lb-l wm-a"/><path class="zc2m5bbql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crosshair-duo" {...props}></Icon>
