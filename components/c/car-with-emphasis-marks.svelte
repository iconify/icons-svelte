<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6h785nef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h6h785nef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-emphasis-marks" {...props}></Icon>
