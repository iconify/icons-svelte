<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc8fm6r7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc8fm6r7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-large-linear" {...props}></Icon>
