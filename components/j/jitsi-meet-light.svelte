<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue2g5nbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ue2g5nbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jitsi-meet-light" {...props}></Icon>
