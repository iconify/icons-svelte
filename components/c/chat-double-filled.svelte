<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh33njbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh33njbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-double-filled" {...props}></Icon>
