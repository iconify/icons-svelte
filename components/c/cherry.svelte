<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/n/nndn0bb0j.css';
import '../../css/c/ctyck5byh.css';
import '../../css/j/jm6531b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><circle class="nndn0bb0j"/><circle class="ctyck5byh"/><path class="jm6531b2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:cherry" {...props}></Icon>
