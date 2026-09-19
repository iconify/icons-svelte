<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0_ewobgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y0_ewobgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:heart-circle-sharp" {...props}></Icon>
