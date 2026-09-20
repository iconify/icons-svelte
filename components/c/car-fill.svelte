<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpu-awb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpu-awb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:car-fill" {...props}></Icon>
