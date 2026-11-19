<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiu53obws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tiu53obws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:excalidraw" {...props}></Icon>
