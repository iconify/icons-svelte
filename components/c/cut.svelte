<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5w_htbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="j5w_htbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cut" {...props}></Icon>
