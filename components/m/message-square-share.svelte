<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p0zfw1uuh.css';
import '../../css/b/bx45vvbjs.css';
import '../../css/g/g9nc5pb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p0zfw1uuh"/><path class="bx45vvbjs"/><path class="g9nc5pb1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-share" {...props}></Icon>
