<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j6jfr6onh.css';
import '../../css/m/mol5oypic.css';
import '../../css/l/llfuwubbz.css';
import '../../css/l/lbrnwbcro.css';
import '../../css/q/qinpu5bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j6jfr6onh wm-a"/><path class="mol5oypic"/><path class="llfuwubbz"/><path class="lbrnwbcro"/><path class="qinpu5bxk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cable" {...props}></Icon>
