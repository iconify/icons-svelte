<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xv5hb_5sx.css';
import '../../css/g/g136touho.css';
import '../../css/b/bht756bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xv5hb_5sx"/><path class="g136touho wm-a"/><path class="bht756bnp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:app-window-duo" {...props}></Icon>
