<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0nz5z_0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="r0nz5z_0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:functions" {...props}></Icon>
