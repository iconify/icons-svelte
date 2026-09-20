<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz_xj2mif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xz_xj2mif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filerun-light" {...props}></Icon>
