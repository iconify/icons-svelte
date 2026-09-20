<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl1y2kbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl1y2kbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:list-sort-descending" {...props}></Icon>
