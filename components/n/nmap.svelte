<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce4z0nbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ce4z0nbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nmap" {...props}></Icon>
