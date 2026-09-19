<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/g/gdvdupecv.css';
import '../../css/w/wxxx193iv.css';
import '../../css/o/ogpl226vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<g class="h01tyzbfu"><path class="gdvdupecv"/><path class="wxxx193iv"/><path class="ogpl226vk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:lasso-tool" {...props}></Icon>
