<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb0-klyri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb0-klyri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-20" {...props}></Icon>
