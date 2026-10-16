<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atn8x1kpb.css';
import '../../css/l/lfo7cvbjq.css';
import '../../css/w/wk-hnobdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<g clip-rule="evenodd" class="atn8x1kpb"><path class="lfo7cvbjq"/><path class="wk-hnobdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:focalboard" {...props}></Icon>
