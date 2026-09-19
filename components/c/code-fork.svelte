<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvaiqfbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1536};
const content = `<path class="rvaiqfbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:code-fork" {...props}></Icon>
