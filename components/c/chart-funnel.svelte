<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/ppt3q08ns.css';
import '../../css/a/az6mvhbpu.css';
import '../../css/f/f221bg_-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ppt3q08ns"/><path class="az6mvhbpu"/><path class="f221bg_-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-funnel" {...props}></Icon>
