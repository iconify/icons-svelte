<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqk3hhf6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":432};
const content = `<path class="rqk3hhf6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:desktop-windows" {...props}></Icon>
