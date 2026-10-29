<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/msbovjbkh.css';
import '../../css/s/s5fsn4tdx.css';
import '../../css/u/uh01hzbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="msbovjbkh"/><path class="s5fsn4tdx wm-a"/><path class="uh01hzbyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chocolate-box-duo" {...props}></Icon>
