<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_9_dmbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_9_dmbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:float-right-sharp" {...props}></Icon>
