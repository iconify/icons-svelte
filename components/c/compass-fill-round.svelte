<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5g2cq1iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5g2cq1iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:compass-fill-round" {...props}></Icon>
