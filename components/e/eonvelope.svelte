<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4zh2mqii.css';
import '../../css/n/nxd5vsn0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4zh2mqii"/><path class="nxd5vsn0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eonvelope" {...props}></Icon>
