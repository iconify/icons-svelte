<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/ff4jdybea.css';
import '../../css/g/gtbtb4krd.css';
import '../../css/g/gqeu1eb-b.css';
import '../../css/p/p-js957rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ff4jdybea wm-k"/><path class="gtbtb4krd wm-a"/><path class="gqeu1eb-b wm-k"/><path class="p-js957rr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:burger-sketch" {...props}></Icon>
