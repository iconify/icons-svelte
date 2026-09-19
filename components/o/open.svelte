<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dsdpatbbu.css';
import '../../css/g/gqt1trakv.css';
import '../../css/z/zf-73sbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="dsdpatbbu"/><path class="gqt1trakv"/><path class="zf-73sbfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:open" {...props}></Icon>
