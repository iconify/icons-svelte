<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9s81cs5j.css';
import '../../css/r/rm6kyddwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x9s81cs5j"/><path class="rm6kyddwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filebrowser-quantum-light" {...props}></Icon>
