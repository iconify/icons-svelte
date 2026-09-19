<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/eqg_32bbr.css';
import '../../css/p/pgwj559ot.css';
import '../../css/d/deucknbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="eqg_32bbr"/><path class="pgwj559ot"/><path class="deucknbez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bandaged-outline" {...props}></Icon>
