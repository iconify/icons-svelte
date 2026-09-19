<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rctcol8zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":408};
const content = `<path class="rctcol8zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:city" {...props}></Icon>
