<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/skgb1wbjs.css';
import '../../css/g/gezngsbej.css';
import '../../css/z/zy_z_lmnz.css';
import '../../css/w/w4v_cgusb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="skgb1wbjs wm-shadow"/><path class="gezngsbej wm-shadow"/><path class="zy_z_lmnz"/><path class="w4v_cgusb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:baseball" {...props}></Icon>
