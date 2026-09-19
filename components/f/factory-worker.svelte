<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jzib17bsz.css';
import '../../css/t/tq0xuccly.css';
import '../../css/i/i6e9c_m2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="jzib17bsz"/><path clip-rule="evenodd" class="tq0xuccly"/><path class="i6e9c_m2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:factory-worker" {...props}></Icon>
