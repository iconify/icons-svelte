<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0x7j6tzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0x7j6tzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:focus-mode" {...props}></Icon>
