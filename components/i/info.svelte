<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfu9axa6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="wfu9axa6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:info" {...props}></Icon>
