<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3ettib1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="w3ettib1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:polyline-dash" {...props}></Icon>
