<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w74_pkbuu.css';
import '../../css/x/xye5qqb6j.css';
import '../../css/o/om2raabrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="w74_pkbuu wm-a"/><path class="xye5qqb6j"/><path class="om2raabrv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:audio-lines" {...props}></Icon>
