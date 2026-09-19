<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rg_xgzhfl.css';
import '../../css/l/ll6bpkbte.css';
import '../../css/v/vmbylbb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rg_xgzhfl"/><path class="ll6bpkbte"/><path class="vmbylbb-t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:many-to-many" {...props}></Icon>
