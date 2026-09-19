<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebldvkbho.css';
import '../../css/o/oz4mxp5be.css';
import '../../css/y/ylly5hb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="oz4mxp5be"/><path class="ylly5hb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:plus" {...props}></Icon>
