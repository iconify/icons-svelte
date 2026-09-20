<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wr-u5pbye.css';
import '../../css/i/i8zp6bckl.css';
import '../../css/r/rm076e2fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wr-u5pbye"/><path class="i8zp6bckl"/><path class="rm076e2fp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-line-bold-duotone" {...props}></Icon>
