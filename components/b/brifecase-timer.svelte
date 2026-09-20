<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/r/rh_fox7ue.css';
import '../../css/b/b40u25bhd.css';
import '../../css/l/lwenppemr.css';
import '../../css/x/x8uq8pl-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="rh_fox7ue"/><path class="b40u25bhd"/><path class="lwenppemr"/><path class="x8uq8pl-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:brifecase-timer" {...props}></Icon>
