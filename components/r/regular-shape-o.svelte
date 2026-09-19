<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up3xwf3il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="up3xwf3il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:regular-shape-o" {...props}></Icon>
