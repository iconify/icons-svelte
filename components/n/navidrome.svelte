<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0ix46b3r.css';
import '../../css/p/p1yx4trbb.css';
import '../../css/d/dcy5gh-xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="r0ix46b3r"/><circle class="p1yx4trbb"/><path class="dcy5gh-xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:navidrome" {...props}></Icon>
