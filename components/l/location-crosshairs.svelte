<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3dsvjbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l3dsvjbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:location-crosshairs" {...props}></Icon>
