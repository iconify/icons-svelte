<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hew4q4b0u.css';
import '../../css/c/ck_6qidwg.css';
import '../../css/g/gfb62bt5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hew4q4b0u"/><path class="ck_6qidwg wm-a"/><path class="gfb62bt5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:contact-duo" {...props}></Icon>
