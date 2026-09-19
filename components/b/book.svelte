<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhj26dnyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1696,"height":1536};
const content = `<path class="vhj26dnyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:book" {...props}></Icon>
