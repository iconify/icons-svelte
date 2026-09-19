<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlp2d-pxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tlp2d-pxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:nintendo-gamecube" {...props}></Icon>
