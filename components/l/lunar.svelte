<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgimn7bxc.css';
import '../../css/t/t0u4brujn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dgimn7bxc"/><path class="t0u4brujn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lunar" {...props}></Icon>
