<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k85w4fbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="k85w4fbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-search" {...props}></Icon>
