<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f589aobdb.css';
import '../../css/i/i278szqpx.css';
import '../../css/y/y-0yi6qaz.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="f589aobdb"/><path clip-rule="evenodd" class="i278szqpx"/><path class="y-0yi6qaz"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:calendar-off" {...props}></Icon>
