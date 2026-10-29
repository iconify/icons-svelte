<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/prthrmbng.css';
import '../../css/y/ym55n8biq.css';
import '../../css/v/v826tbcka.css';
import '../../css/v/v7oxsddra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="prthrmbng"/><path class="wm-a ym55n8biq"/><path class="v826tbcka wm-s"/><path class="v7oxsddra wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mistletoe" {...props}></Icon>
