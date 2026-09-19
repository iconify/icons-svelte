<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1oyd7blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1oyd7blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:outdoor-motion-sensor-temperature" {...props}></Icon>
