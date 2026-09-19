<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqhlopbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="sqhlopbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-item-6" {...props}></Icon>
