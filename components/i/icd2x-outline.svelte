<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/otw5jg97e.css';
import '../../css/k/kcy22cc0q.css';
import '../../css/v/vfc_tmbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="otw5jg97e"/><path clip-rule="evenodd" class="kcy22cc0q"/><path clip-rule="evenodd" class="vfc_tmbcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:icd2x-outline" {...props}></Icon>
