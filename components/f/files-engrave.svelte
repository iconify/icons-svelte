<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gjj-z7sbn.css';
import '../../css/z/zh-auabps.css';
import '../../css/j/j91e-mbhk.css';
import '../../css/y/yui4pigey.css';
import '../../css/v/vqyclfbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gjj-z7sbn wm-k"/><path class="wm-a zh-auabps"/><path class="j91e-mbhk wm-shadow"/><path class="wm-k yui4pigey"/><path class="vqyclfbmt wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:files-engrave" {...props}></Icon>
