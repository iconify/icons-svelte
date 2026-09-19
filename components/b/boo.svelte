<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv82bmbkc.css';
import '../../css/x/xb-3e0r0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yv82bmbkc"/><path class="xb-3e0r0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:boo" {...props}></Icon>
