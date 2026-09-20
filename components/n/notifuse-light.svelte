<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8gl_zb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w8gl_zb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notifuse-light" {...props}></Icon>
