<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pfbpfv12y.css';
import '../../css/n/np4vdmbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="pfbpfv12y"/><path clip-rule="evenodd" class="np4vdmbzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:heart-rate-pulse-graph-flat" {...props}></Icon>
