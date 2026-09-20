<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyf8v3b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyf8v3b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gamepad-circle" {...props}></Icon>
