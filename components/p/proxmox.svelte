<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yldie4v8a.css';
import '../../css/h/hiz_q4neb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yldie4v8a"/><path class="hiz_q4neb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxmox" {...props}></Icon>
