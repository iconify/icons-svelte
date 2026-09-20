<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doy8l7bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="doy8l7bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:rocket" {...props}></Icon>
