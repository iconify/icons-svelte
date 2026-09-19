<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnnorwv9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":770};
const content = `<path class="jnnorwv9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:camera" {...props}></Icon>
