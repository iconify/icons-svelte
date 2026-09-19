<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2isvmm5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2isvmm5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chart-line" {...props}></Icon>
