<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlfijw3hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":456};
const content = `<path class="zlfijw3hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:puzzle-piece" {...props}></Icon>
