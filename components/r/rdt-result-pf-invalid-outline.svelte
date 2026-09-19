<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o9-4x4bcb.css';
import '../../css/w/wvouqqeyv.css';
import '../../css/n/nf593dbwl.css';
import '../../css/o/o8sha-b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="o9-4x4bcb"/><path clip-rule="evenodd" class="wvouqqeyv"/><path clip-rule="evenodd" class="nf593dbwl"/><path class="o8sha-b1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rdt-result-pf-invalid-outline" {...props}></Icon>
