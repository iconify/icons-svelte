<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dr-lmjbud.css';
import '../../css/l/lsl7qwgdg.css';
import '../../css/g/gzr2x4p5b.css';
import '../../css/w/w1nca4blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="dr-lmjbud"/><path class="lsl7qwgdg"/><path clip-rule="evenodd" class="gzr2x4p5b"/><path class="w1nca4blz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:agriculture-worker" {...props}></Icon>
