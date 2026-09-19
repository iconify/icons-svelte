<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um91gjswm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="um91gjswm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:exposure-alt" {...props}></Icon>
