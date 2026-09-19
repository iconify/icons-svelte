<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fec6_tvnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fec6_tvnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:lower-brightness" {...props}></Icon>
