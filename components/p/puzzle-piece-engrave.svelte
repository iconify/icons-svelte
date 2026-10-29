<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b_uq6-6qm.css';
import '../../css/j/j-0g3nb-u.css';
import '../../css/o/on6hknbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b_uq6-6qm"/><path class="j-0g3nb-u wm-shadow"/><path class="on6hknbag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:puzzle-piece-engrave" {...props}></Icon>
