<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bqi8s4bgh.css';
import '../../css/p/p3y-97bfh.css';
import '../../css/l/lo-bdo53p.css';
import '../../css/t/tcjvbpb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bqi8s4bgh wm-k"/><path class="p3y-97bfh wm-shadow"/><path class="lo-bdo53p wm-k"/><path class="tcjvbpb5r wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gamepad-engrave" {...props}></Icon>
