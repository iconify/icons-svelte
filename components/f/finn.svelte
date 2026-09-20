<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6q3dwxxu.css';
import '../../css/x/xtwgksb_s.css';
import '../../css/r/rp7oy-b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d6q3dwxxu"/><path class="xtwgksb_s"/><path class="rp7oy-b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:finn" {...props}></Icon>
