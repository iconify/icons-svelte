<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/n/nwbhzkbcg.css';
import '../../css/y/ycul966hb.css';
import '../../css/c/c9-gn0brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="nwbhzkbcg"/><path clip-rule="evenodd" class="ycul966hb"/><path class="c9-gn0brd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:click" {...props}></Icon>
