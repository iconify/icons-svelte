<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zydcpabso.css';
import '../../css/x/xdj82wxwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zydcpabso"/><path class="xdj82wxwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bag-check-outline" {...props}></Icon>
