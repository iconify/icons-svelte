<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fju0pbb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="fju0pbb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:polyline-pt" {...props}></Icon>
