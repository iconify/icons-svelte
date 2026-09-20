<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8c9_rbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8c9_rbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ping-pong-line" {...props}></Icon>
