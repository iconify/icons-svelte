<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e3728q2fv.css';
import '../../css/j/j1tznqzdp.css';
import '../../css/y/ykgkceq4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e3728q2fv"/><path class="j1tznqzdp wm-k"/><path class="wm-a ykgkceq4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:footprints-sketch" {...props}></Icon>
