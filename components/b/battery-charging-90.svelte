<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm2a5nb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm2a5nb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-90" {...props}></Icon>
