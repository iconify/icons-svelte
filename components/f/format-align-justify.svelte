<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll2jandrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ll2jandrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-align-justify" {...props}></Icon>
