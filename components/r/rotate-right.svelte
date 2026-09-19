<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5oe30boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d5oe30boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:rotate-right" {...props}></Icon>
