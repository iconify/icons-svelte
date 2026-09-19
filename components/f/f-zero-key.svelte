<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/r8cyu3bwz.css';
import '../../css/a/a1qy3pb2q.css';
import '../../css/e/elttmdb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="r8cyu3bwz"/><rect class="a1qy3pb2q"/><path class="elttmdb8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:f-zero-key" {...props}></Icon>
