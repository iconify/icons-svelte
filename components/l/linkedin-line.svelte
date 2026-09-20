<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy9vcx_4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy9vcx_4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:linkedin-line" {...props}></Icon>
