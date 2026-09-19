<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hwp43mulz.css';
import '../../css/r/r6v_pabhc.css';
import '../../css/j/je6hsf0yt.css';
import '../../css/y/ywibotp-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="hwp43mulz"/><path class="r6v_pabhc"/><path clip-rule="evenodd" class="je6hsf0yt"/><path class="ywibotp-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:microphone-1-outline" {...props}></Icon>
