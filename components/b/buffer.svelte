<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri9iarbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ri9iarbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:buffer" {...props}></Icon>
