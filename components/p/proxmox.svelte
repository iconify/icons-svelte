<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yldie4v8a.css';
import '../../css/x/x7cs9_u7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yldie4v8a"/><path class="x7cs9_u7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxmox" {...props}></Icon>
