<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf6vixbyo.css';
import '../../css/q/qhl_bsc2l.css';
import '../../css/j/j4fy5j07e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sf6vixbyo"/><path class="qhl_bsc2l"/><path class="j4fy5j07e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:compreface" {...props}></Icon>
