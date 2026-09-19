<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev--0sa9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ev--0sa9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-asterisk" {...props}></Icon>
