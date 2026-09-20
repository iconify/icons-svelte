<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1_y4b3pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="m1_y4b3pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:heart-rate" {...props}></Icon>
