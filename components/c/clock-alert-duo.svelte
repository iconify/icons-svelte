<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xltax3bxw.css';
import '../../css/j/j3l-vfqkm.css';
import '../../css/h/hmp16njeg.css';
import '../../css/f/f78e21b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xltax3bxw"/><path class="j3l-vfqkm wm-s"/><path class="hmp16njeg"/><path class="f78e21b0t wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clock-alert-duo" {...props}></Icon>
