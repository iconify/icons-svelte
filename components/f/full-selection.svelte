<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/c/c-elrgb8n.css';
import '../../css/n/nw9mp7bns.css';
import '../../css/t/t355hjgxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="c-elrgb8n"/><path class="nw9mp7bns"/><path class="t355hjgxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:full-selection" {...props}></Icon>
