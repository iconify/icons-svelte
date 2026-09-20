<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq2rymb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq2rymb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chat" {...props}></Icon>
