<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mffjr_bbm.css';
import '../../css/w/w8gg6ab1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mffjr_bbm"/><path class="w8gg6ab1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dialysis" {...props}></Icon>
