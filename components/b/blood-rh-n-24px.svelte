<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wm3k4sq6x.css';
import '../../css/f/fm0pxnbwp.css';
import '../../css/v/vqsfm7b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wm3k4sq6x"/><path clip-rule="evenodd" class="fm0pxnbwp"/><path class="vqsfm7b3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-rh-n-24px" {...props}></Icon>
