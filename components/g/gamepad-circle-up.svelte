<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp6inmbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp6inmbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gamepad-circle-up" {...props}></Icon>
