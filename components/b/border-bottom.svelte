<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw1a0h_9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="vw1a0h_9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:border-bottom" {...props}></Icon>
