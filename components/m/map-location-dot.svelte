<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxk7nn9kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gxk7nn9kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:map-location-dot" {...props}></Icon>
