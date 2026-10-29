<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hwj-ajb-x.css';
import '../../css/q/q4fjqwbqj.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/c/c-a4_nb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hwj-ajb-x"/><path class="q4fjqwbqj wm-a"/><path class="yw4fz_b6b"/><path class="c-a4_nb-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lucky-coin-duo" {...props}></Icon>
