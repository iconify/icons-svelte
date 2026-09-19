<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_fpweb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="x_fpweb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:360" {...props}></Icon>
