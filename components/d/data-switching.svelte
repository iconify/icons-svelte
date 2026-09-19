<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/p/pv-ktibnd.css';
import '../../css/x/x901lharp.css';
import '../../css/k/k-42yk6zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="pv-ktibnd"/><path class="x901lharp"/><path class="k-42yk6zs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:data-switching" {...props}></Icon>
