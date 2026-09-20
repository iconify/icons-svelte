<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rylovv_qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rylovv_qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-fast" {...props}></Icon>
