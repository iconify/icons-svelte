<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsv4enbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="hsv4enbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-south" {...props}></Icon>
