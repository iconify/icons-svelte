<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdf-s7bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sdf-s7bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-geometric-polygon-polygon-octangle-design-geometric-shape-shapes" {...props}></Icon>
