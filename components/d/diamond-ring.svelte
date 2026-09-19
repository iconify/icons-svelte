<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/rbb69cszp.css';
import '../../css/y/ym_q5kb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="rbb69cszp"/><path class="ym_q5kb_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:diamond-ring" {...props}></Icon>
