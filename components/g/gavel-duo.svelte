<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/na6msx4zs.css';
import '../../css/k/kjyj4ubca.css';
import '../../css/t/tx1l_fszj.css';
import '../../css/a/aydzuvbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="na6msx4zs"/><path class="kjyj4ubca wm-s"/><path class="tx1l_fszj"/><path class="aydzuvbkz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gavel-duo" {...props}></Icon>
