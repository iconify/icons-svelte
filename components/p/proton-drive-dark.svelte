<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieqwf_b3i.css';
import '../../css/y/yasd2p6xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ieqwf_b3i"/><path class="yasd2p6xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-drive-dark" {...props}></Icon>
