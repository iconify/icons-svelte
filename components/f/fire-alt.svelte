<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcv5y0bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="dcv5y0bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:fire-alt" {...props}></Icon>
