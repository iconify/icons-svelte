<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m1ox2hhhb.css';
import '../../css/l/l-if2ibsb.css';
import '../../css/a/a74ox2l4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m1ox2hhhb"/><path class="l-if2ibsb wm-a"/><path class="a74ox2l4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:regex-duo" {...props}></Icon>
