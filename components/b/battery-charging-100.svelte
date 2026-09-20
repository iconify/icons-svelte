<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r417itu3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r417itu3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-100" {...props}></Icon>
