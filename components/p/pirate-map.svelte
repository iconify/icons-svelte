<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvyy43brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="gvyy43brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:pirate-map" {...props}></Icon>
