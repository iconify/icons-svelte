<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxzhnfb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pxzhnfb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:fonticons" {...props}></Icon>
