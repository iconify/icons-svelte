<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4xrz4bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="j4xrz4bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:4" {...props}></Icon>
