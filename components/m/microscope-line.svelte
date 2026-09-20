<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixw31ybfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixw31ybfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:microscope-line" {...props}></Icon>
