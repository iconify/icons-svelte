<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_dovporp.css';
import '../../css/r/rc7tgcbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_dovporp"/><path class="rc7tgcbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:airpipe" {...props}></Icon>
