<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m3jp7g4ta.css';
import '../../css/o/ofygbeg8k.css';
import '../../css/x/xh2vlidti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="m3jp7g4ta"/><path class="ofygbeg8k"/><path class="xh2vlidti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hourglass2-duotone" {...props}></Icon>
