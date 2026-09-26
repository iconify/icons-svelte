<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d68ervb4k.css';
import '../../css/r/rtpvlhbro.css';
import '../../css/y/y7x24zb6u.css';
import '../../css/v/vsz1bjqxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d68ervb4k"/><path class="rtpvlhbro"/><path class="y7x24zb6u"/><path clip-rule="evenodd" class="vsz1bjqxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bonfire-bold" {...props}></Icon>
