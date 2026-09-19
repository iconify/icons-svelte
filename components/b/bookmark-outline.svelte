<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0o3vwkfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k0o3vwkfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bookmark-outline" {...props}></Icon>
