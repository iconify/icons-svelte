<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch_l3abug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch_l3abug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-10" {...props}></Icon>
