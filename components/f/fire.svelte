<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiuw0lbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":464};
const content = `<path class="xiuw0lbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:fire" {...props}></Icon>
