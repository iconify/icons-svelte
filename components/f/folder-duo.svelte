<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnc6ln0cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cnc6ln0cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:folder-duo" {...props}></Icon>
