<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrtsi0prd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qrtsi0prd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:hex-map" {...props}></Icon>
