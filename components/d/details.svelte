<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4i32xbmp.css';
import '../../css/h/hs0i9ccsp.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/s/sr5zzomxa.css';
import '../../css/a/a_yqdob_i.css';
import '../../css/z/zxl-v6htc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="x4i32xbmp"/><circle class="hs0i9ccsp"/><g class="ij2x_72vy"><path class="sr5zzomxa"/><circle class="a_yqdob_i"/><path class="zxl-v6htc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:details" {...props}></Icon>
