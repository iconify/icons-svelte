<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/obsscdhly.css';
import '../../css/d/dff5sqbum.css';
import '../../css/e/eibp0ub2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="obsscdhly"/><path class="dff5sqbum"/><path class="eibp0ub2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hotspot" {...props}></Icon>
