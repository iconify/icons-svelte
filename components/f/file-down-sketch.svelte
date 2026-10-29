<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eioevte6k.css';
import '../../css/r/rx57ytblr.css';
import '../../css/v/vyj2zpbth.css';
import '../../css/b/b1hapgd5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eioevte6k"/><path class="rx57ytblr wm-a"/><path class="vyj2zpbth wm-k"/><path class="b1hapgd5x wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-down-sketch" {...props}></Icon>
