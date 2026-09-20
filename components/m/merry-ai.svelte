<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ye__qpbqz.css';
import '../../css/x/xuemwg1jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<g class="ft5dv1b6b"><rect class="ye__qpbqz"/><path class="xuemwg1jm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:merry-ai" {...props}></Icon>
