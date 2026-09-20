<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk-2meg8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zk-2meg8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-keep-light" {...props}></Icon>
