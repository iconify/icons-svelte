<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mm_aw0bii.css';
import '../../css/c/ce_gtac-e.css';
import '../../css/v/vc1hcbbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mm_aw0bii"/><path class="ce_gtac-e"/><path class="vc1hcbbrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bridge-two" {...props}></Icon>
