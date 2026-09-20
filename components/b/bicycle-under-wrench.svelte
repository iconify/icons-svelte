<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtvpuzbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gtvpuzbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-under-wrench" {...props}></Icon>
