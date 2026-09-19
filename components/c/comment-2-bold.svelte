<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rhz_qccmf.css';
import '../../css/e/evv5kswbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rhz_qccmf"/><path class="evv5kswbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-2-bold" {...props}></Icon>
