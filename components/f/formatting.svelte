<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akk0b-1ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="akk0b-1ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:formatting" {...props}></Icon>
