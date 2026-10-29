<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x1a8p8bbx.css';
import '../../css/x/xeipbgbue.css';
import '../../css/c/cdyj0qbkl.css';
import '../../css/l/ll5-hyzyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="x1a8p8bbx"/><path class="wm-a xeipbgbue"/><path class="cdyj0qbkl wm-k"/><path class="ll5-hyzyo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ice-cream-sketch" {...props}></Icon>
