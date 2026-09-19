<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nldomubfm.css';
import '../../css/k/kkesx9btg.css';
import '../../css/b/bwz--2-hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nldomubfm"/><path clip-rule="evenodd" class="kkesx9btg"/><path class="bwz--2-hu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rmnh" {...props}></Icon>
