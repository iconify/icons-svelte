<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/ftv5at4kc.css';
import '../../css/g/gfnus2l-k.css';
import '../../css/x/xk3bi4f7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ftv5at4kc wm-deco"/><path class="gfnus2l-k wm-k"/><path class="wm-a xk3bi4f7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:holly-blueprint" {...props}></Icon>
