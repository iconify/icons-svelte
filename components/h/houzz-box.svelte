<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cioctv_tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cioctv_tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:houzz-box" {...props}></Icon>
