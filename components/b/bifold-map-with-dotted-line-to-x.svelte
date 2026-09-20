<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni-v-ubcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ni-v-ubcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bifold-map-with-dotted-line-to-x" {...props}></Icon>
