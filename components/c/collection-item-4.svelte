<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr56h3nhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="dr56h3nhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-item-4" {...props}></Icon>
