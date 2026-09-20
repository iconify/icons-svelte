<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar1p11b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ar1p11b4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:overseerr-light" {...props}></Icon>
