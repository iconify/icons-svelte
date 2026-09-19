<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j78zgrbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j78zgrbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:format-status" {...props}></Icon>
