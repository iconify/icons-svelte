<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzqhaxd9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lzqhaxd9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:brush-filled" {...props}></Icon>
