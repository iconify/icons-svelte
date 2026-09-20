<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep6q_wb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep6q_wb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-down-drop" {...props}></Icon>
