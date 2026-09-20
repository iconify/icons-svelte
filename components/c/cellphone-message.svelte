<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9q2_w4fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9q2_w4fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-message" {...props}></Icon>
