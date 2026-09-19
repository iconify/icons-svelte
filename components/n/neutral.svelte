<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n87g3vegy.css';
import '../../css/s/sfpa_vabo.css';
import '../../css/j/j76_xebgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="n87g3vegy"/><path class="sfpa_vabo"/><path clip-rule="evenodd" class="j76_xebgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:neutral" {...props}></Icon>
