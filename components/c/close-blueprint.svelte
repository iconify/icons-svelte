<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lb34b3syz.css';
import '../../css/h/hjfiyp-px.css';
import '../../css/h/hrjatl9nv.css';
import '../../css/c/cp-zj9t8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lb34b3syz wm-deco"/><path class="hjfiyp-px wm-deco"/><path class="hrjatl9nv"/><path class="cp-zj9t8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:close-blueprint" {...props}></Icon>
