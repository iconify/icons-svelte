<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5hs5qbej.css';
import '../../css/x/xl_i265-u.css';
import '../../css/d/d42sx8bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":16};
const content = `<path class="z5hs5qbej"/><path class="xl_i265-u"/><path class="d42sx8bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:books" {...props}></Icon>
