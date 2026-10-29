<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/ymsh4jbls.css';
import '../../css/w/wqb-0n4qk.css';
import '../../css/t/t8-4j7c2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ymsh4jbls"/><path class="wm-a wqb-0n4qk"/><path class="t8-4j7c2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mail-duo" {...props}></Icon>
