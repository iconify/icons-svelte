<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5ytazb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="h5ytazb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-pacific-o" {...props}></Icon>
