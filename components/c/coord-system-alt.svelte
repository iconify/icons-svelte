<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug25vmbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ug25vmbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:coord-system-alt" {...props}></Icon>
