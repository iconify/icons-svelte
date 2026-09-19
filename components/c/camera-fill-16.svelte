<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myl142blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="myl142blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:camera-fill-16" {...props}></Icon>
