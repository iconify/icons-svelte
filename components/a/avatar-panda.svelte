<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mdvkx-geo.css';
import '../../css/x/xarb4rskp.css';
import '../../css/s/ssdqucc2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mdvkx-geo"/><path class="xarb4rskp"/><path class="ssdqucc2z wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-panda" {...props}></Icon>
