<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/l/l7f1sjbcp.css';
import '../../css/t/tt34m96-v.css';
import '../../css/x/x43575byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="l7f1sjbcp wm-shadow"/><path class="tt34m96-v"/><path class="x43575byl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:app-window" {...props}></Icon>
