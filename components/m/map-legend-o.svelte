<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7h9c3bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="y7h9c3bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-legend-o" {...props}></Icon>
