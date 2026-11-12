<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4_720ovn.css';
import '../../css/r/rm6kyddwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4_720ovn"/><path class="rm6kyddwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filebrowser-quantum-light" {...props}></Icon>
