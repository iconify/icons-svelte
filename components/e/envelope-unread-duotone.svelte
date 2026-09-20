<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w4brwwbzi.css';
import '../../css/f/f1h18-blq.css';
import '../../css/x/xhcoxr84o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w4brwwbzi"/><path class="f1h18-blq"/><path class="xhcoxr84o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:envelope-unread-duotone" {...props}></Icon>
