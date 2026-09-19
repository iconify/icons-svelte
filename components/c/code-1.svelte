<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8xj0kbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x8xj0kbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:code-1" {...props}></Icon>
