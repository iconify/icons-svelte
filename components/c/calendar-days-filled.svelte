<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lbq113d_q.css';
import '../../css/j/jxbxvmfyx.css';
import '../../css/t/tr6mc7b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lbq113d_q"/><path class="jxbxvmfyx"/><path class="tr6mc7b3u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-days-filled" {...props}></Icon>
