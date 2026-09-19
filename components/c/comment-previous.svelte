<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0ignm61z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w0ignm61z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:comment-previous" {...props}></Icon>
