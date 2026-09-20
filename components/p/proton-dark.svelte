<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdp5qyblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sdp5qyblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-dark" {...props}></Icon>
