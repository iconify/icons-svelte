<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkaybslkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":488,"height":488};
const content = `<path class="xkaybslkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:grid-off" {...props}></Icon>
