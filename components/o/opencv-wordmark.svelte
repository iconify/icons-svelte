<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulipixb_y.css';
import '../../css/c/cl9z5d_3w.css';
import '../../css/h/hsahbabwh.css';
import '../../css/a/aizck2ejj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ulipixb_y"/><path class="cl9z5d_3w"/><path class="hsahbabwh"/><path class="aizck2ejj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:opencv-wordmark" {...props}></Icon>
