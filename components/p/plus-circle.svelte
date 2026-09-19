<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7ex6tb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="n7ex6tb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:plus-circle" {...props}></Icon>
