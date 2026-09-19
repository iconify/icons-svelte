<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d90u9e2cl.css';
import '../../css/y/yedrxvbcn.css';
import '../../css/u/umro7hm1n.css';
import '../../css/j/jhzkcobgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="d90u9e2cl"/><path clip-rule="evenodd" class="yedrxvbcn"/><path class="umro7hm1n"/><path clip-rule="evenodd" class="jhzkcobgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:page-break-outline" {...props}></Icon>
