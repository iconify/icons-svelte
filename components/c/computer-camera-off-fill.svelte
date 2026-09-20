<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjzv1qksk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjzv1qksk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:computer-camera-off-fill" {...props}></Icon>
