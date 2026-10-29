<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s1r0ezbnv.css';
import '../../css/s/shte9bcuj.css';
import '../../css/u/up4lun9xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="s1r0ezbnv"/><path class="shte9bcuj wm-a"/><path class="up4lun9xh wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bell-ring" {...props}></Icon>
