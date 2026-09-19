<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/j/jywzibzfz.css';
import '../../css/f/fw8rx6b9c.css';
import '../../css/c/cuh8gyztp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="jywzibzfz"/><path class="fw8rx6b9c"/><path class="cuh8gyztp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:enter-key" {...props}></Icon>
