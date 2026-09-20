<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k08wnob5f.css';
import '../../css/w/wyv77qbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k08wnob5f"/><path class="wyv77qbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:little-chat-light" {...props}></Icon>
