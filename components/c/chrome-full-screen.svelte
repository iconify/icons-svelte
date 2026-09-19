<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv6zixa_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zv6zixa_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chrome-full-screen" {...props}></Icon>
