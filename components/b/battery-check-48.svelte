<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri3k7ob7e.css';
import '../../css/a/a-4s07bqr.css';
import '../../css/p/py4nxfbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ri3k7ob7e"/><path class="a-4s07bqr"/><path class="py4nxfbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-check-48" {...props}></Icon>
