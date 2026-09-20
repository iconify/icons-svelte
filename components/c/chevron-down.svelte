<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1ay_wb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h1ay_wb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chevron-down" {...props}></Icon>
