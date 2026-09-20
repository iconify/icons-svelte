<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpfa0s5nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dpfa0s5nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qemu-light" {...props}></Icon>
