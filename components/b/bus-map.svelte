<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj9yn6a4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="aj9yn6a4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:bus-map" {...props}></Icon>
