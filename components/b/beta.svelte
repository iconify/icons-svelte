<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh9_36b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wh9_36b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:beta" {...props}></Icon>
