<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/y/yez7skblq.css';
import '../../css/n/n6bczebbq.css';
import '../../css/h/h2uo0wbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="yez7skblq"/><circle class="n6bczebbq"/><path class="h2uo0wbmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:camera-one" {...props}></Icon>
