<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vno3wljjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vno3wljjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camera-2-off-fill" {...props}></Icon>
