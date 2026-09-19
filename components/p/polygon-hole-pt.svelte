<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yor3-q3xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yor3-q3xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:polygon-hole-pt" {...props}></Icon>
