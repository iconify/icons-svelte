<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv6m5xotf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uv6m5xotf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:caret-square-right" {...props}></Icon>
