<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gn0ui-b3h.css';
import '../../css/o/oivip8bjf.css';
import '../../css/j/j5ce3sbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gn0ui-b3h"/><path class="oivip8bjf wm-a"/><path class="j5ce3sbao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bell-concierge-duo" {...props}></Icon>
