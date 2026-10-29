<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uhbvnmlqs.css';
import '../../css/c/crjbpijjy.css';
import '../../css/e/e_6oe7ajk.css';
import '../../css/r/rvo70qbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uhbvnmlqs"/><path class="crjbpijjy wm-a"/><path class="e_6oe7ajk wm-k"/><path class="rvo70qbei wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plane-takeoff-sketch" {...props}></Icon>
