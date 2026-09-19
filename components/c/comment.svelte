<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2z5zjbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="p2z5zjbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:comment" {...props}></Icon>
