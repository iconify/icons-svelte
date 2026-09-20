<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_glx4ama.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_glx4ama"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:package-delivered" {...props}></Icon>
