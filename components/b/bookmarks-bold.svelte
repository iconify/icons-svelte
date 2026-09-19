<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/rb0i5fyzc.css';
import '../../css/k/ktmahbbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="rb0i5fyzc"/><path class="ktmahbbai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bookmarks-bold" {...props}></Icon>
