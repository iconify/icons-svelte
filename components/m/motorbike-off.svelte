<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-v5uabwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-v5uabwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:motorbike-off" {...props}></Icon>
