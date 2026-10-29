<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/ztptv0bde.css';
import '../../css/a/aczwgrt9b.css';
import '../../css/b/b0tfb6skh.css';
import '../../css/t/tc5tthbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ztptv0bde"/><path class="aczwgrt9b wm-a"/><path class="b0tfb6skh wm-k"/><path class="tc5tthbjf wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-x-sketch" {...props}></Icon>
