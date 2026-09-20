<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd_610ovi.css';
import '../../css/r/r0k4s_6cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qd_610ovi"/><path class="r0k4s_6cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hhf-technology" {...props}></Icon>
