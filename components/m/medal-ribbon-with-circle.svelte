<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtli1d3xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dtli1d3xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:medal-ribbon-with-circle" {...props}></Icon>
