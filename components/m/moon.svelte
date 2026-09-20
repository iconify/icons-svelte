<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk3a44bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jk3a44bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:moon" {...props}></Icon>
