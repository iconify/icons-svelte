<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm2utoh2v.css';
import '../../css/b/bubzgdclu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="bm2utoh2v"/><path class="bubzgdclu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:angle-double-left" {...props}></Icon>
