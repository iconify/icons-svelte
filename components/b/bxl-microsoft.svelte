<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uugvgqb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uugvgqb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-microsoft" {...props}></Icon>
