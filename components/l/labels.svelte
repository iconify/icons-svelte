<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsy3h9rol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":408};
const content = `<path class="rsy3h9rol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:labels" {...props}></Icon>
