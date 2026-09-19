<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l_71t2bfr.css';
import '../../css/w/wm1wz458c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="l_71t2bfr"/><path class="wm1wz458c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:piechart" {...props}></Icon>
