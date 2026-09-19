<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/q97o_r-5j.css';
import '../../css/u/u47j2_boj.css';
import '../../css/n/nwipaonmi.css';
import '../../css/i/i94q9of-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><ellipse class="q97o_r-5j"/><path class="u47j2_boj"/><path class="nwipaonmi"/><path class="i94q9of-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:data-all" {...props}></Icon>
