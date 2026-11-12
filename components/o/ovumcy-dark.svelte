<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh61nybyw.css';
import '../../css/r/rhmy8zb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fh61nybyw"/><path class="rhmy8zb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ovumcy-dark" {...props}></Icon>
