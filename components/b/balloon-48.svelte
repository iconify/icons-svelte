<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b76cn79oc.css';
import '../../css/j/j4audb3xv.css';
import '../../css/f/fvcv6nbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b76cn79oc"/><path class="j4audb3xv"/><path class="fvcv6nbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:balloon-48" {...props}></Icon>
