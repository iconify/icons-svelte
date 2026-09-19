<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gv1rnmbhg.css';
import '../../css/l/l2q3qg5ur.css';
import '../../css/j/j5ytutb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="gv1rnmbhg"/><path clip-rule="evenodd" class="l2q3qg5ur"/><path clip-rule="evenodd" class="j5ytutb_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-atlas-bold" {...props}></Icon>
