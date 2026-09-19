<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atz9pabfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":440};
const content = `<path class="atz9pabfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hdr-off" {...props}></Icon>
