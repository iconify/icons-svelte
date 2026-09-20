<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0qakpzvw.css';
import '../../css/m/mhn4ay1xq.css';
import '../../css/t/ty23m0b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r0qakpzvw"/><path class="mhn4ay1xq"/><path class="ty23m0b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:langfuse-dark" {...props}></Icon>
