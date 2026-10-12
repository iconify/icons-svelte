<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8aj85itm.css';
import '../../css/y/ypv4l3ivv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r8aj85itm"/><path class="ypv4l3ivv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-spreadsheet-stroke-20" {...props}></Icon>
