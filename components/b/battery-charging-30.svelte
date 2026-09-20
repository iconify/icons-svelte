<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uumv_0bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uumv_0bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-30" {...props}></Icon>
