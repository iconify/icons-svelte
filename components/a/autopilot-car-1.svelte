<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-657w83o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-657w83o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:autopilot-car-1" {...props}></Icon>
