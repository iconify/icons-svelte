<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb7td8ixk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="zb7td8ixk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:replay-30" {...props}></Icon>
