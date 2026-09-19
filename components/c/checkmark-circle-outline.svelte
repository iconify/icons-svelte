<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg5j7ibl.css';
import '../../css/d/d_cpnh_xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="d_cpnh_xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:checkmark-circle-outline" {...props}></Icon>
