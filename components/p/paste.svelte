<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vghglv62h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":472};
const content = `<path class="vghglv62h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:paste" {...props}></Icon>
