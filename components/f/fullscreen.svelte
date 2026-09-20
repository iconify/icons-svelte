<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h74cu0bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h74cu0bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:fullscreen" {...props}></Icon>
