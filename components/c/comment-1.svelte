<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp8queyss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yp8queyss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-1" {...props}></Icon>
