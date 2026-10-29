<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dout1oble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dout1oble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:filter-solid" {...props}></Icon>
