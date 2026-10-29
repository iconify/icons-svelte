<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jv3lt9s1r.css';
import '../../css/r/rdjxs30_z.css';
import '../../css/p/pwsazko7z.css';
import '../../css/y/yn_loccov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jv3lt9s1r"/><path class="rdjxs30_z wm-a"/><path class="pwsazko7z wm-s"/><path class="wm-a yn_loccov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:jack-o-lantern" {...props}></Icon>
