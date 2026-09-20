<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt1553bbb.css';
import '../../css/i/iua5r4byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mt1553bbb"/><path class="iua5r4byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camera-2-off-fill" {...props}></Icon>
