<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8o8gmbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u8o8gmbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:envelope-square-solid" {...props}></Icon>
