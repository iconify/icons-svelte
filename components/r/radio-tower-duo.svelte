<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gveujlbog.css';
import '../../css/i/iib4vtwgi.css';
import '../../css/b/b88gxzbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gveujlbog"/><path class="iib4vtwgi wm-a"/><path class="b88gxzbev"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:radio-tower-duo" {...props}></Icon>
