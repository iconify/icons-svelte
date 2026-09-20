<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hopwxcc7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hopwxcc7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:fullscreen-exit" {...props}></Icon>
