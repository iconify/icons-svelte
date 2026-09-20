<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uin1j8l2y.css';
import '../../css/l/lgs3ws6-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uin1j8l2y"/><path class="lgs3ws6-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ford" {...props}></Icon>
