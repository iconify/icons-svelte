<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn4rg314c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="vn4rg314c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cloud-circle" {...props}></Icon>
