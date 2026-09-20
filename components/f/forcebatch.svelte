<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayuc712mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ayuc712mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:forcebatch" {...props}></Icon>
