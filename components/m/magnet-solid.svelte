<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-l1pd0_w.css';
import '../../css/t/tdrlb7b0w.css';
import '../../css/h/h9z2q_b6q.css';
import '../../css/a/axq84z9hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path class="tdrlb7b0w"/><path clip-rule="evenodd" class="h9z2q_b6q"/><path clip-rule="evenodd" class="axq84z9hc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:magnet-solid" {...props}></Icon>
