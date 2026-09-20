<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skwfvjj7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="skwfvjj7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:airplane-enabled-solid" {...props}></Icon>
