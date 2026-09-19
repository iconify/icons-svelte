<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz_1fupeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xz_1fupeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-3" {...props}></Icon>
