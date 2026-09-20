<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7q30fbjm.css';
import '../../css/k/k42dqu5-u.css';
import '../../css/r/reokt-boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e7q30fbjm"/><path class="k42dqu5-u"/><path class="reokt-boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-opni" {...props}></Icon>
