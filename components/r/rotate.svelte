<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq5e0lw6b.css';
import '../../css/d/d2ja3uk6v.css';
import '../../css/d/dsk89bmik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<g class="pq5e0lw6b"><path class="d2ja3uk6v"/><path class="dsk89bmik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:rotate" {...props}></Icon>
