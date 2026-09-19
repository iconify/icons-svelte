<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hw2s293_a.css';
import '../../css/m/mlcmwpbbf.css';
import '../../css/l/l28zvvb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hw2s293_a"/><path clip-rule="evenodd" class="mlcmwpbbf"/><path class="l28zvvb-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:i-documents-denied2x-outline" {...props}></Icon>
