<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dgwlyubic.css';
import '../../css/o/ohjklpuln.css';
import '../../css/o/oaildwbhf.css';
import '../../css/o/oc1d-ibzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="dgwlyubic"/><path class="ohjklpuln"/><path class="oaildwbhf"/><path class="oc1d-ibzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hotel" {...props}></Icon>
