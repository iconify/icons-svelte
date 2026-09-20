<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrhpp6bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nrhpp6bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:file-browser-light" {...props}></Icon>
