<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti4q6eknm.css';
import '../../css/f/flz8fyicu.css';
import '../../css/b/b8c_z7brc.css';
import '../../css/j/j-dpmubjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="flz8fyicu"/><path class="b8c_z7brc"/><path class="j-dpmubjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:kungfu" {...props}></Icon>
