<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh4_mkb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="sh4_mkb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:plus-circle-o" {...props}></Icon>
