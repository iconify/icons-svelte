<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1yv8q8vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="y1yv8q8vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:alarm-plus" {...props}></Icon>
