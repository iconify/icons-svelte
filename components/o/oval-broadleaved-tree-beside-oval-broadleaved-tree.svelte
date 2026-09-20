<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp8gz9b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rp8gz9b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:oval-broadleaved-tree-beside-oval-broadleaved-tree" {...props}></Icon>
