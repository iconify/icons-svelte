<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zgro9p05h.css';
import '../../css/o/or5oqnxmr.css';
import '../../css/f/ffkv7ob9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="zgro9p05h"/><path clip-rule="evenodd" class="or5oqnxmr"/><path class="ffkv7ob9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:biopsy2x-outline" {...props}></Icon>
