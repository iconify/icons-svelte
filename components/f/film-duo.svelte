<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/td00sn06k.css';
import '../../css/f/fqe0e-3jo.css';
import '../../css/e/euj49csjz.css';
import '../../css/s/stgsv1byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="td00sn06k"/><path class="fqe0e-3jo wm-a"/><path class="euj49csjz"/><path class="stgsv1byj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:film-duo" {...props}></Icon>
