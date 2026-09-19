<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0a4mhdhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="i0a4mhdhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:book" {...props}></Icon>
