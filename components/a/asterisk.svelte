<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy4mifo5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1472,"height":1536};
const content = `<path class="iy4mifo5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:asterisk" {...props}></Icon>
