<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmut65bkr.css';
import '../../css/i/idc7-cb9a.css';
import '../../css/r/rp7oy-b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmut65bkr"/><path class="idc7-cb9a"/><path class="rp7oy-b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:finn-light" {...props}></Icon>
