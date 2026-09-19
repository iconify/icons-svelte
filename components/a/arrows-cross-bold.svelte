<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/ds-o0-bao.css';
import '../../css/c/cihcivbvm.css';
import '../../css/o/o5ig9ksrn.css';
import '../../css/d/d5al52b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="ds-o0-bao"/><path class="cihcivbvm"/><path class="o5ig9ksrn"/><path class="d5al52b3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-cross-bold" {...props}></Icon>
