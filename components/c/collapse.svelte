<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bag6wvkzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bag6wvkzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:collapse" {...props}></Icon>
