<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eh56edcyw.css';
import '../../css/t/t8a7fpred.css';
import '../../css/a/awkx36b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eh56edcyw wm-k"/><path class="t8a7fpred wm-k"/><path class="awkx36b2i wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:playground-sketch" {...props}></Icon>
