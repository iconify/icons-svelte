<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl1hj1dvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xl1hj1dvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:discard" {...props}></Icon>
