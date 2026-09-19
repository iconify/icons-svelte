<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ifw-3tbef.css';
import '../../css/k/kcbnqacwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ifw-3tbef"/><path clip-rule="evenodd" class="kcbnqacwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contraceptive-diaphragm-outline" {...props}></Icon>
