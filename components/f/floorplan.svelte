<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8f5z6b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r8f5z6b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:floorplan" {...props}></Icon>
