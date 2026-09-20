<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxzwpsbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":150,"height":150};
const content = `<path class="gxzwpsbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nx-dark" {...props}></Icon>
