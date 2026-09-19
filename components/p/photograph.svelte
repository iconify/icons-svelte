<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/a/a7ebtkb2c.css';
import '../../css/p/pzexhzbmt.css';
import '../../css/f/fphtxumqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="a7ebtkb2c"/><path class="pzexhzbmt"/><path class="fphtxumqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:photograph" {...props}></Icon>
