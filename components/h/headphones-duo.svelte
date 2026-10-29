<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j5cyxpnlx.css';
import '../../css/r/r0v6itbzy.css';
import '../../css/l/ltpyfabni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j5cyxpnlx"/><path class="r0v6itbzy wm-a"/><path class="ltpyfabni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:headphones-duo" {...props}></Icon>
