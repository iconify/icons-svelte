<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t31v27vgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="t31v27vgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:proj-conic" {...props}></Icon>
