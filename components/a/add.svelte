<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0v5ewb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j0v5ewb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:add" {...props}></Icon>
