<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_a5_ubdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_a5_ubdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:drag-handle-solid" {...props}></Icon>
