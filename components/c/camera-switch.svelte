<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq5z-cv1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="eq5z-cv1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:camera-switch" {...props}></Icon>
