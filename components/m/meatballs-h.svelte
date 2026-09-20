<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7j5rbdjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j7j5rbdjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:meatballs-h" {...props}></Icon>
