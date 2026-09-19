<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf8i4wb_q.css';
import '../../css/h/hn3vxocrc.css';
import '../../css/m/mhn7bwbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mf8i4wb_q"/><path class="hn3vxocrc"/><path class="mhn7bwbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-done-all" {...props}></Icon>
