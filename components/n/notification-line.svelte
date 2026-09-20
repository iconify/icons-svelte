<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8795uznh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8795uznh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notification-line" {...props}></Icon>
