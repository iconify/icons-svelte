<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tx1l_fszj.css';
import '../../css/a/aydzuvbkz.css';
import '../../css/k/kjyj4ubca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tx1l_fszj"/><path class="aydzuvbkz wm-a"/><path class="kjyj4ubca wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gavel" {...props}></Icon>
