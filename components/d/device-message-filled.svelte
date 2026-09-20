<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/th240zbjx.css';
import '../../css/l/ll2wlbm4o.css';
import '../../css/p/p501uebdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="th240zbjx"/><path class="ll2wlbm4o"/><path class="p501uebdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:device-message-filled" {...props}></Icon>
