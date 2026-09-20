<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exdltnb9b.css';
import '../../css/r/rg-moybam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="exdltnb9b"/><path class="rg-moybam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:offline-gateway-filled" {...props}></Icon>
