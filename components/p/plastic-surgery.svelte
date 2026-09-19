<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/t/t4s6mac-y.css';
import '../../css/w/w8gxl9-7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="pr52f_b5y"><path class="t4s6mac-y"/><path class="w8gxl9-7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:plastic-surgery" {...props}></Icon>
