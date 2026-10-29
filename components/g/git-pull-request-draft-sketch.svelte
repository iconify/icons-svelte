<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cwfqxbbmp.css';
import '../../css/y/ydi4l6wia.css';
import '../../css/y/y79632q_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cwfqxbbmp"/><path class="wm-k ydi4l6wia"/><path class="wm-a y79632q_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-pull-request-draft-sketch" {...props}></Icon>
