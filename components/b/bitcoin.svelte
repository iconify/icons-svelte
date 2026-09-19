<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mgq_3dz5s.css';
import '../../css/g/gac3uxrkd.css';
import '../../css/m/mvmqk0bcf.css';
import '../../css/m/mbpu8ibdy.css';
import '../../css/n/nad5dccpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><circle class="mgq_3dz5s"/><path class="gac3uxrkd"/><path class="mvmqk0bcf"/><path class="mbpu8ibdy"/><path class="nad5dccpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bitcoin" {...props}></Icon>
