<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg5af8b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zg5af8b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:picture-filled" {...props}></Icon>
