<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9e-6i4ua.css';
import '../../css/r/ry96p-bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l9e-6i4ua"/><path class="ry96p-bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-clean-car-cable-charge" {...props}></Icon>
