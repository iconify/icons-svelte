<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/ycrv7o_lb.css';
import '../../css/h/h97kjdagp.css';
import '../../css/i/itg-c1b2z.css';
import '../../css/n/ncvignbbk.css';
import '../../css/b/bd2_erdbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ycrv7o_lb"/><path class="h97kjdagp"/><path class="itg-c1b2z"/><path class="ncvignbbk"/><path class="bd2_erdbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:move-x" {...props}></Icon>
