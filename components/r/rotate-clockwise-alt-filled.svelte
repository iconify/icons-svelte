<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr-yqlb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lr-yqlb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rotate-clockwise-alt-filled" {...props}></Icon>
