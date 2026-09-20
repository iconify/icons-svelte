<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcl4k4fpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcl4k4fpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-right-bold-circle-outline" {...props}></Icon>
