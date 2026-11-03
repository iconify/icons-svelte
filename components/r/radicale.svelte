<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsnyatslk.css';
import '../../css/e/eacht384o.css';
import '../../css/e/eomgn6xaw.css';
import '../../css/v/vabgvhplk.css';
import '../../css/t/tawi2lsdc.css';
import '../../css/v/vr2clrb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":300};
const content = `<path class="qsnyatslk"/><path class="eacht384o"/><g class="eomgn6xaw"><path class="vabgvhplk"/><path class="tawi2lsdc"/><path class="vr2clrb9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:radicale" {...props}></Icon>
