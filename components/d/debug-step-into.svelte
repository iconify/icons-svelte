<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqms5zblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqms5zblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:debug-step-into" {...props}></Icon>
