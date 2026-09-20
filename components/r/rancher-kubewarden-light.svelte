<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri65of2nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ri65of2nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-kubewarden-light" {...props}></Icon>
