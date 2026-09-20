<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lmmvpew-x.css';
import '../../css/z/zbkydgbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":42};
const content = `<g class="cuyn6tgcc"><path class="lmmvpew-x"/><path class="zbkydgbar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:productboard" {...props}></Icon>
