<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upmtxfbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="upmtxfbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nirvati-light" {...props}></Icon>
