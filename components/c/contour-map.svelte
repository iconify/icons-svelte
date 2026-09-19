<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdibqed7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mdibqed7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:contour-map" {...props}></Icon>
