<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1rt0mcpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m1rt0mcpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:expand-screen-filled" {...props}></Icon>
