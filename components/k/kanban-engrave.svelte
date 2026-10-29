<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j28mambxy.css';
import '../../css/f/fd5etqajb.css';
import '../../css/l/lg-8n1num.css';
import '../../css/i/itg9jgtim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j28mambxy"/><path class="fd5etqajb wm-shadow"/><path class="lg-8n1num"/><path class="itg9jgtim wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:kanban-engrave" {...props}></Icon>
