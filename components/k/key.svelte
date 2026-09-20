<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xrby5qbhn.css';
import '../../css/x/xas7j-b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xrby5qbhn"/><path class="xas7j-b1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:key" {...props}></Icon>
