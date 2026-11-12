<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znqd3cctx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="znqd3cctx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:arlo-light" {...props}></Icon>
