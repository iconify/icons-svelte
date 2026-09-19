<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/i/ib2bsphlp.css';
import '../../css/q/q97o_r-5j.css';
import '../../css/v/vf4h32bmh.css';
import '../../css/y/y4vjg0k3v.css';
import '../../css/n/nwipaonmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ib2bsphlp"/><ellipse class="q97o_r-5j"/><path class="vf4h32bmh"/><path class="y4vjg0k3v"/><path class="nwipaonmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:data-three" {...props}></Icon>
