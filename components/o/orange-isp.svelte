<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8oh0_brq.css';
import '../../css/z/zb1p0hbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x8oh0_brq"/><path class="zb1p0hbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orange-isp" {...props}></Icon>
