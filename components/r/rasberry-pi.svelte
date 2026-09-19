<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py5u74dhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py5u74dhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:rasberry-pi" {...props}></Icon>
