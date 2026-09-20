<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym6wy1brw.css';
import '../../css/g/gtz84wbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ym6wy1brw"/><path class="gtz84wbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dji-logbook" {...props}></Icon>
