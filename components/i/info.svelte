<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/m/mca4zbboh.css';
import '../../css/e/ey28qh55f.css';
import '../../css/q/qx29uub7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="mca4zbboh"/><path class="ey28qh55f"/><path class="qx29uub7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:info" {...props}></Icon>
