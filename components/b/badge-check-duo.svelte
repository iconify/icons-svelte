<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lfddx0u7v.css';
import '../../css/i/i4t66q3an.css';
import '../../css/h/hooc3vbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lfddx0u7v"/><path class="i4t66q3an wm-a"/><path class="hooc3vbcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:badge-check-duo" {...props}></Icon>
