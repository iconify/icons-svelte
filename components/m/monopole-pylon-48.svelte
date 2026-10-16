<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-l0jd7mu.css';
import '../../css/r/rt3djzbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p-l0jd7mu"/><path class="rt3djzbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monopole-pylon-48" {...props}></Icon>
