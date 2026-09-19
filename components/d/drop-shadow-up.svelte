<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/r/r0pn3fb6p.css';
import '../../css/k/kwzrzeqtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path clip-rule="evenodd" class="r0pn3fb6p"/><path class="kwzrzeqtd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:drop-shadow-up" {...props}></Icon>
