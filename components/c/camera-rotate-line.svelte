<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6-2_0kgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6-2_0kgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camera-rotate-line" {...props}></Icon>
