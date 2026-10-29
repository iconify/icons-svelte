<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j-h64fb-q.css';
import '../../css/c/cw36_6mco.css';
import '../../css/o/orw_fqitx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j-h64fb-q"/><path class="cw36_6mco wm-a"/><path class="orw_fqitx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-network-duo" {...props}></Icon>
