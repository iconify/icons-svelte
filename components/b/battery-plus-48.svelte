<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri3k7ob7e.css';
import '../../css/a/a-4s07bqr.css';
import '../../css/v/v-3r9t8cb.css';
import '../../css/c/cal94qbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ri3k7ob7e"/><path class="a-4s07bqr"/><path class="v-3r9t8cb"/><path class="cal94qbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-plus-48" {...props}></Icon>
