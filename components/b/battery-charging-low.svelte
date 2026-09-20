<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk3_t9boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk3_t9boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-low" {...props}></Icon>
