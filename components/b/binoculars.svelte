<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gaam40bfx.css';
import '../../css/g/gdnuq8wfy.css';
import '../../css/g/g8_iol2hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gaam40bfx"/><path class="gdnuq8wfy"/><path class="g8_iol2hx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:binoculars" {...props}></Icon>
