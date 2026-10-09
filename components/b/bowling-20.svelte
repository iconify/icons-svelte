<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzq6l3b3u.css';
import '../../css/d/dfcj5z_lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uzq6l3b3u"/><path class="dfcj5z_lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bowling-20" {...props}></Icon>
