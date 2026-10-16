<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6_s1zkbf.css';
import '../../css/l/l8i64_wsn.css';
import '../../css/r/r41ol3t2y.css';
import '../../css/s/sxqz2irrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6_s1zkbf"/><path class="l8i64_wsn"/><path class="r41ol3t2y"/><path class="sxqz2irrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-environment-20" {...props}></Icon>
