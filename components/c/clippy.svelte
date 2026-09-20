<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwmrae3sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwmrae3sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clippy" {...props}></Icon>
