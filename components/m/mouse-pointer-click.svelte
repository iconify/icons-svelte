<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/y/ydu6i3b1c.css';
import '../../css/q/q8nqxnf2b.css';
import '../../css/h/heg0hjblo.css';
import '../../css/n/nyyaa3u0w.css';
import '../../css/p/p4ra5frnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow ydu6i3b1c"/><path class="q8nqxnf2b wm-shadow"/><path class="heg0hjblo"/><path class="nyyaa3u0w"/><path class="p4ra5frnv wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:mouse-pointer-click" {...props}></Icon>
