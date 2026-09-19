<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/i/ihrkb6bvf.css';
import '../../css/c/c12_yhz0x.css';
import '../../css/u/u0j7o5bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="ihrkb6bvf"/><rect class="c12_yhz0x"/><path class="u0j7o5bno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:exclude-selection" {...props}></Icon>
