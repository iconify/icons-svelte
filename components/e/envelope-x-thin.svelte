<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-82h-3mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b-82h-3mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:envelope-x-thin" {...props}></Icon>
