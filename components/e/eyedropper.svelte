<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv29y0z8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mv29y0z8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:eyedropper" {...props}></Icon>
