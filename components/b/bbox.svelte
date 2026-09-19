<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um1gt6bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="um1gt6bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:bbox" {...props}></Icon>
