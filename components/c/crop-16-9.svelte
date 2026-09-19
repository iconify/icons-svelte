<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0iw95o7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="y0iw95o7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:crop-16-9" {...props}></Icon>
