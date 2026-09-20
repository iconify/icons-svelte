<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnnn5it5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gnnn5it5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:jump" {...props}></Icon>
