<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iozmfob3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iozmfob3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:location-target-2" {...props}></Icon>
