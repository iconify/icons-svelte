<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s06ydqbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="s06ydqbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:panorama-horizontal" {...props}></Icon>
