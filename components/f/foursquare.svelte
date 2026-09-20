<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toly2kmve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="toly2kmve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:foursquare" {...props}></Icon>
