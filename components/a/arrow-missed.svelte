<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f53u21b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="f53u21b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:arrow-missed" {...props}></Icon>
