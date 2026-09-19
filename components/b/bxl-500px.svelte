<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4xwqdi_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4xwqdi_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-500px" {...props}></Icon>
