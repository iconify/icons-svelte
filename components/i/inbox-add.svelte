<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw6fp4b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bw6fp4b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:inbox-add" {...props}></Icon>
