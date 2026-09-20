<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm59pb2yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":791.27};
const content = `<path class="rm59pb2yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hack-the-box" {...props}></Icon>
