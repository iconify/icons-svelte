<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy1rgmbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fy1rgmbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fnos-light" {...props}></Icon>
